#### Test 50650278d0426ce_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/AlertService( 5843): Beginning updateAlertNotification
D/AlertService( 5843): No fired or scheduled alerts
I/NotificationManager( 5843): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5843): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5843): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5843): No events found starting within 1 week.
--------- beginning of system
I/ActivityManager(  995): Killing 5843:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_10013/pid_5843/cgroup.procs: No such file or directory
D/AndroidRuntime( 6025): 
D/AndroidRuntime( 6025): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6025): CheckJNI is OFF
D/AndroidRuntime( 6025): Calling main entry com.android.commands.am.Am
I/ActivityManager(  995): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  995): setTaskToReturnTo : TaskRecord{2ad497e4 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  995): setTaskToReturnTo : TaskRecord{2ad497e4 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  995): AppWindowTokenEx init.. 
D/ContextHelper(  995): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  995): Focus left window: Window{21c4309e u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6025): Shutting down VM
W/ActivityManager(  995): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  995): RTC_WAKEUP set : Alarm{1f6ee849 type 0 when 1449508289983 com.android.providers.contacts} when 1449508289983
V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{1e75554e type 2 when 60616 com.google.android.talk} when 60616
V/AlarmManager(  995): RTC_WAKEUP set : Alarm{3ea8ff7c type 0 when 1449681148089 com.android.vending} when 1449681148089
D/Finsky  ( 5526): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/SplitWindow(  995): check instance of lgWin Window{1555785a u0 Starting com.test.thalitest}
I/ActivityManager(  995): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6055 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/HotwordDetector( 1964): Closing mic
I/MicrophoneInputStream( 1964): mic_close com.google.android.apps.gsa.speech.audio.u@26fc919
V/AudioRecord( 1964): stop()
D/AudioRecord( 1964): AudioRecord->stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
V/AudioFlinger(  278): Record stopped OK
V/AudioPolicyManager(  278): stopInput() input 17
V/AudioPolicyService(  278): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  278): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  278): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  278): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  278): ThreadBase::setParameters() routing=0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3848000
I/WindowStateAnimator(  995): Starting window displayed
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
I/SystemUI[Framework](  995): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  995): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  995): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  995): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  995): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@306ef261,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  995): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1374): draw background and invalidate : color = 8000000
D/BarTransitions( 1374): draw background and invalidate : color = 7070707
V/audio_hw_primary(  278): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  278): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  278): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  278): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  278): disable_audio_route: exit
E/audio_hw_primary(  278): disable_snd_device: enter 144
D/hardware_info(  278): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  278): disable_snd_device: snd_device(144: lg-vr-handset-mic)
I/NotificationManager(  995): android: cancelAsUser(2) by android
V/audio_hw_primary(  278): stop_input_stream: exit: status(0)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioPolicyManager(  278): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  278): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  278): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  278): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioPolicyService(  278): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  278): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  278): setParameters(): io 17, keyvalue hotword_active=0, calling pid 278
V/AudioFlinger(  278): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  278): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  278): in_set_parameters: exit: status(0)
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3848000
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioRecord( 1964): stop()
V/AudioRecord( 1964): stop()
V/AudioRecord( 1964): stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
V/AudioPolicyManager(  278): releaseInput() 17
V/AudioPolicyManager(  278): closeInput(17)
V/AudioFlinger(  278): closeInput() 17
V/AudioSystem(  278): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  995): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1964): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1753): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): ThreadBase::exit
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioSystem( 1991): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): releasing 16 from 1964 for -1
V/AudioFlinger(  278): RecordThread 0xb3848000 exiting
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioSystem( 2692): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): purging stale effects
V/AudioSystem( 3175): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  278): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  278): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  278): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioPolicyManager(  278): releaseInput() exit
V/AudioFlinger(  278): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  278): removeClient_l() pid 1964, calling pid 278
I/HotwordRecognitionRnr( 1964): Stopping hotword detection.
I/HotwordRecognitionRnr( 1964): Hotword detection finished
D/libc-netbsd( 5526): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5526): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5526): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5526): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5526): propertyValue:false
D/libc-netbsd( 5526): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5526): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ContextHelper( 6055): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/libc-netbsd( 5526): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5526): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 95301120385; DSPS: 3221507; Offset : -3022731946
I/WebViewFactory( 6055): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6055): Time to load native libraries: 2 ms (timestamps 5372-5374)
I/LibraryLoader( 6055): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6055): Binding Chromium to main looper Looper (main, tid 1) {2a0e36c8}
I/LibraryLoader( 6055): Expected native library version number "",actual native library version number ""
I/chromium( 6055): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6055): Initializing chromium process, singleProcess=true
W/art     ( 6055): Attempt to remove local handle scope entry from IRT, ignoring
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SysUtils( 6055): ApplicationContext is null in ApplicationStatus
I/NotificationManager(  995): android: cancelAsUser(2) by android
W/chromium( 6055): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6055): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6055): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6055): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6055): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6055): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6055): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6055): Remote Branch: 
I/Adreno-EGL( 6055): Local Patches: 
I/Adreno-EGL( 6055): Reconstruct Branch: 
I/qtaguid ( 5526): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5526): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5526): untagSocket(41) failed with errno -22
D/Finsky  ( 5526): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
V/AudioPolicyService(  278): registerClient() client 0xb57ea420, uid 10316
D/BluetoothManagerService(  995): Message: 20
D/BluetoothManagerService(  995): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a3fe9c8:true
D/BluetoothAdapterService(657717108)( 1991): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d367c6a
I/ActivityManager(  995): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6108 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  995): android: cancelAsUser(2) by android
,W/ResourcesManager( 6108): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6108): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6108): VM with version 2.1.0 has multidex support
I/MultiDex( 6108): install
I/MultiDex( 6108): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6108): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/art     ( 6055): Attempt to remove local handle scope entry from IRT, ignoring
I/qtaguid ( 5526): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5526): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5526): untagSocket(41) failed with errno -22
,W/AwContents( 6055): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6055): CordovaWebView is running on device made by: LGE
,W/art     ( 6055): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6055): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityThread( 6108): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6108): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@376477ca: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6108): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6108): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6108): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1734): callingUid 10006, callindPid: 1734
,D/ChimeraCfgMgr( 6108): Reading stored module config
E/MDM     ( 1734): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4245): Restart initialization of location
,I/Activity( 6055): Activity.onPostResume() called 
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
D/OpenGLRenderer( 6055): Render dirty regions requested: true
I/OpenGLRenderer( 6055): Initialized EGL, version 1.4
,D/ChimeraCfgMgr( 6108): Loading module com.google.android.gms.car from APK com.google.android.gms
D/OpenGLRenderer( 6055): Enabling debug mode 0
W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
D/Atlas   ( 6055): Validating map...
,D/SplitWindow(  995): check instance of lgWin Window{231a88be u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6055): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  995): Focus entered window: Window{231a88be u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  995): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  995): Displayed com.test.thalitest/.MainActivity: +1s307ms
I/Timeline(  995): Timeline: Activity_windows_visible id: ActivityRecord{2124544d u0 com.test.thalitest/.MainActivity t220} time:96149
I/Timeline( 6055): Timeline: Activity_idle id: android.os.BinderProxy@134e0c37 time:96156
,I/art     ( 5526): CheckpointMarkThreadRoots callback created = 0xb05848c0
,I/art     ( 5526): CheckpointMarkThreadRoots callback created = 0xb0584890
,D/CAR.SERVICE( 6108): Connecting to CarCallService...
,D/NativeLibraryUtils( 6108): Install completed successfully. count=14 extracted=0
,I/art     ( 6108): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6108): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/BindingManager( 6055): Cannot call determinedVisibility() - never saw a connection for the pid: 6055
,D/CAR.SERVICE( 6108): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6108): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6108): Creating a new PhoneAdapter instance
,W/ActivityManager(  995): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6108): setListener: com.google.android.gms.car.dn@3ff6e921
W/ActivityManager(  995): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6108): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6108): Starting CarCallService with initial phone null
I/NotificationManager( 6108): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6108): Package validated; name: com.android.vending
,I/NotificationManager( 5526): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5526): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/JsMessageQueue( 6055): Set native->JS mode to OnlineEventsBridgeMode
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  995): android: cancelAsUser(2) by android
D/jxcore_app_log( 6055): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618654208
D/JX-Cordova( 6055): jxcore cordova android initializing
,I/qtaguid ( 5526): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5526): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5526): untagSocket(41) failed with errno -22
,I/art     ( 6055): CheckpointMarkThreadRoots callback created = 0x9c1fa490
,I/art     ( 6055): CheckpointMarkThreadRoots callback created = 0x9c1fa460
,W/ResourcesManager( 5526): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5526): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5967): Internal timer expired: 1
,W/ResourcesManager( 5526): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5526): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 5526): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  995): RTC_WAKEUP set : Alarm{41d1b34 type 0 when 1449681150863 com.android.vending} when 1449681150863
,D/Finsky  ( 5526): [674] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1734): client connected with version: 8296000
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  995): android: cancelAsUser(2) by android
,D/libc-netbsd( 5526): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5526): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5526): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5526): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10036
,D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 5526): propertyValue:false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  995): Process com.google.android.apps.plus (pid 5479) has died
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  995): Process com.android.gallery3d (pid 5912) has died
,W/jxcore-log( 6055): Initializing JXcore engine
,W/jxcore-log( 6055): JXcore engine is ready
I/ActivityManager(  995): Process com.android.contacts (pid 5395) has died
W/jxcore-log( 6055): Starting JXcore engine
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/.test.thalitest( 6055): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7399]" dev="sockfs" ino=7399 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6055): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6055): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7582]" dev="sockfs" ino=7582 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6055): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6055): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6055): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[28389]" dev="sockfs" ino=28389 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,I/ActivityManager(  995): Process com.lge.lockscreensettings (pid 5414) has died
,W/jxcore-log( 6055): Platform android
W/jxcore-log( 6055): 
W/jxcore-log( 6055): Process ARCH arm
W/jxcore-log( 6055): 
,I/ActivityManager(  995): Process com.android.providers.calendar (pid 5944) has died
V/AlarmManager(  995): RTC_WAKEUP set : Alarm{37749ccc type 0 when 1449681153491 com.google.android.googlequicksearchbox} when 1449681153491
,I/jxcore-log( 6055): JXcore Cordova bridge is ready!
I/jxcore-log( 6055): 
,W/jxcore-log( 6055): JXcore engine is started
I/chromium( 6055): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 6055): Toggling radios to true
I/jxcore-log( 6055): 
,D/BluetoothAdapter( 6055): enable(): BT is already enabled..!
D/WifiServiceImplEx(  995): setWifiEnabled: true pid=6055, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  995): setWifiEnabled: true pid=6055, uid=10316
D/WifiServiceImplEx(  995): disconnect pid=6055, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  995): reconnect pid=6055, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6055): Radios toggled
I/jxcore-log( 6055): 
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2815): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2815): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  995): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1804): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  995): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/LGWifiP2pService(  995): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  995): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  995): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  274): Clearing all IP addresses on wlan0
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
,V/NativeCrypto( 1734): Read error: ssl=0xb0458800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1734): SSL shutdown failed: ssl=0xb0458800: I/O error during system call, Broken pipe
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  995): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  995): ignoring duplicate network state non-change
D/ConnectivityService(  995): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  995): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:33.894 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/WifiHS20(  995): hidePasspointNotification off =false
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): ValidatedState{ when=-6ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): DefaultState{ when=-19ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): Forcing reevaluation
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/ActivityManager(  995): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6200 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/WifiStateMachine(  995): Start Disconnecting Watchdog 1
D/WifiHS20(  995): hidePasspointNotification off =false
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  995): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  995): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2815): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,D/CommandListener(  274): Clearing all IP addresses on wlan0
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:33.989 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  995): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  995): disableDataServiceNotify
D/DSQN    (  995): stop dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
D/WifiHS20(  995): hidePasspointNotification off =false
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:33.999 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  995): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  995):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  995):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  995): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  995): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): Disconnected - quitting
D/CSLegacyTypeTracker(  995): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  995): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  995): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiNetworkAgent(  995): NetworkAgent: NetworkAgent channel lost
W/QCNEJ   ( 1841): |CORE| No family connected
D/Tethering(  995): MasterInitialState.processMessage what=3
V/NetworkPolicy(  995): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  995): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  995): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  995): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1841): |CORE| No family connected
I/QCNEJ   ( 1841): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
V/NetworkPolicy(  995): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  995): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  995): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  995): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  995): Removing idletimer
I/QCNEJ   ( 1841): |CORE| sendDefaultNwMsg: default = -1
D/WifiHS20(  995): hidePasspointNotification off =false
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DhcpStateMachine(  995): StoppedState
D/DhcpStateMachine(  995): StoppedState{ when=-73ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1753): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  995): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:34.048 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:34.048 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiServerServiceExt(  995): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  995): setSupplicantStateDISCONNECTED
D/WIFI    (  995): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  995):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt(  995): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  995): setSupplicantStateSCANNING
,D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6200): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6200): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6200): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
W/ResourcesManager( 6200): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6200): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/IndexDatabaseHelper( 6200): Using schema version: 115
I/IndexDatabaseHelper( 6200): Index is fine
,V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
I/ActivityManager(  995): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6225 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6225): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6225): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6225): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
I/PCSuite ( 6225): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6225): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6225): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
I/PCSuite ( 6225): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6225): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6225): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
I/PCSuite ( 6225): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6225): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6225): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
,I/ActivityManager(  995): Process com.google.android.gms:car (pid 6108) has died
W/ActivityManager(  995): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2815): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/LocSvc_java(  995): onReceive
,I/wpa_supplicant( 2815): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:35.161 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:35.174 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  995): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  995): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,I/wpa_supplicant( 2815): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2815): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  995): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  995): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:35.228 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/WifiServiceExtension(  995): setVHTCapabilityType  : false
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:35.234 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/WiFiOffLoadBroadcast( 6200): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
I/WifiServerServiceExt(  995): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  995): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  995): setSecurityType  : 2
V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:35.28 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:35.297 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  995): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  995): Got NetworkAgent Messenger
D/ConnectivityService(  995): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,D/ConnectivityService(  995): NetworkAgent connected
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
E/WifiConfigStore(  995): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
E/WifiConfigStore(  995): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Setting iface cfg
E/WifiStateMachine(  995): Start Dhcp Watchdog 2
D/DhcpStateMachine(  995): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  995): WaitBeforeStartState
D/WifiServerServiceExt(  995): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  995): setSupplicantStateGROUP_HANDSHAKE
D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
D/ConnectivityService(  995): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
E/WifiStateMachine(  995): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  995): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  995): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@421e583 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  995): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@421e583 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  995): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  995): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  995): DHCP Start wake lock is acquired.
D/CommandListener(  274): Setting iface cfg
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper(  995): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  995): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  995): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  995): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  995): setSupplicantStateCOMPLETED
D/ConnectivityService(  995): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  995): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  995): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  995): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  995): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService(  995): ignoring duplicate network state non-change
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:35.459 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:35.461 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  995): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  995): Adding iface wlan0 to network 101
,D/WifiHS20(  995): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  995): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  995): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:35.482 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:35.484 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 3
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
E/ConnectivityService(  995): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  995): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  995): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  274): netlink response contains error (File exists)
D/ConnectivityService(  995): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  995): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  995): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  995): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  995): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  995): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  995): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  995): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  995):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): Connected
D/ConnectivityService(  995):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  995):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  995):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
D/ConnectivityService(  995):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  995): currentScore = 0, newScore = 20
D/ConnectivityService(  995):    accepting network in place of null
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/ConnectivityService(  995): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIcon,Id=(null)
D/WIFI    (  995): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  995):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 3
D/TelephonyNetworkFactory-1( 1753): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
E/ConnectivityService(  995): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  995): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  995): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): [LWD] Start DNSResolver start to wait
D/ConnectivityService(  995): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  995): [e] list.add(nai) empty : false size: 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): [LWD] wait 500ms before dns check
D/ConnectivityService(  995): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  995): MasterInitialState.processMessage what=3
D/ConnectivityService(  995): validation of new default Network = false
D/ConnectivityService(  995): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  995): enableDataServiceNotify 
D/DSQN    (  995): start dsqn bin
W/QCNEJ   ( 1841): |CORE| No family connected
I/QCNEJ   ( 1841): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1841): |CORE| sendDefaultNwMsg: default = 1
,D/ConnectivityService(  995): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  995):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  995):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  995): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
,V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy(  995): [LG_RESTRICTED] checkMobilePolicy_type()
I/DSQN    ( 6268): DSQN samuel.seo ver 141203
,E/DSQN    ( 6268): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6268): created command queue thread
I/DSQN    ( 6268): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6268): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
I/PCSuite ( 6225): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6225): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6200): MCCMNC not supported: null
,I/PCSuite ( 6225): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6225): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/DhcpStateMachine(  995): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  995): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  995): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6272): version 5.5.6 starting
,E/dhcpcd  ( 6272): get_duid: Read-only file system
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1991): Disconnected process message: 10, size: 0
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  995): battery changed pluggedType: 2
D/HeadsetStateMachine( 1991): Disconnected process message: 10, size: 0
I/dhcpcd  ( 6272): wlan0: rebinding lease of 192.168.1.134
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/dhcpcd  ( 6272): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6272): wlan0: leased 192.168.1.134 for 86400 seconds
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): [LWD] DNSResolver start dns
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out(  995): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6268): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6268): restart monitoring
,D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6268): dsqn report finish
D/DSQN    (  995): DSQM DsqnNotification wlan0  1
D/DSQN    (  995): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 17:12:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449681156113], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449681156091]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): Validated
D/ConnectivityService(  995): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  995): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  995):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  995):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  995):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  995): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  995): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  995):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  995):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  995): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  995): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  995): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
D/WIFI    (  995): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  995):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1753): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  995): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  995): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  995): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  995): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  995): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  995): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  995): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  995): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  995): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  995): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  995): RunningState
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  995): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  995): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  995): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  995): onReceive
D/LocSvc_java(  995): got connectivity action
,D/LocSvc_java(  995): broadcast - no network connections
D/LocSvc_java(  995): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  995): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  995): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  995): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  995): ignore wifi update if we are not in OPENING or CLOSING
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/GpsLocationProvider(  995): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  995): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6308 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
,D/LocSvc_java(  995): onReceive
D/LocSvc_java(  995): got connectivity action
D/LocSvc_java(  995): broadcast - no network connections
D/LocSvc_java(  995): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  995): Sending msg: 4 arg1:0 arg2:1
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  995): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  995): identical MTU - not setting
D/Nat464Xlat(  995): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  995): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  995):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  995):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  995): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  995): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  995): enableDataServiceNotify 
D/DSQN    (  995): start dsqn bin
D/LocSvc_java(  995): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  995): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  995): ignore wifi update if we are not in OPENING or CLOSING
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:37.161 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/DSQN    (  995): dsqn is running restart
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524295
,D/GpsLocationProvider(  995): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DSQN    ( 6334): DSQN samuel.seo ver 141203
E/DSQN    ( 6334): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6334): created command queue thread
I/DSQN    ( 6334): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6334): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/GpsLocationProvider(  995): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  995): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/MusicStore( 6308): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6308): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6308): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6308): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6308): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6308): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6308): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6308): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b8830cd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6308): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6308): GMSCore installation verified
,I/ConfigStore( 6308): Config Database version: 1
,I/art     (  995): Explicit concurrent mark sweep GC freed 78329(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.453ms total 169.792ms
,I/MediaRouter( 6308): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6308): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6308): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6308): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  995): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6352 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6308): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6308): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 6352): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6352): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6352): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/NotificationManager( 6308): com.google.android.music: cancel(1061) by com.google.android.music
,I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:12:38.354 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/LGEmail ( 6352): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,V/WifiInternetCheck(  995): Single check msg out of sync, ignoring.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/LGEmail ( 6352): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/ConnectivityService(  995): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  995): onReceive
D/LocSvc_java(  995): got connectivity action
D/LocSvc_java(  995): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  995): Sending msg: 4 arg1:1 arg2:1
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  995): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  995): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  995): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 6308): type=WIFI subType= reason=null isConnected=true
,I/NotificationManager( 1964): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,D/GpsLocationProvider(  995): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  995): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/eas_req ( 6352): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  995): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6385 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 6352): JNI_OnLoad()
,I/HubEmail( 6352): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6352): registerNatives()
I/HubEmail( 6352): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6352): registerNativeMethods()
I/HubEmail( 6352): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6352): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6352): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6385): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6385): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6385): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6385): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6385): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6385): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 6385): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6385): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  995): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6410 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6385): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6385): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6385): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6385): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6385): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6385): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  995): Killing 5526:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10036/pid_5526/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6410): onCreate
,W/AppUp4:DB( 6410):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6410):  setFingerPrint start
I/AppUp4:DB( 6410):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6410):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6410):  SDK version = 0
I/AppUp4:DB( 6410):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6410): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6410): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6410): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6410): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6410): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6410): onReceive
I/AppUp4:CustModeStarterReceiver( 6410): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/AppUp4:CustFacade( 6410): Context : android.app.ReceiverRestrictedContext@236e7361
D/AppUp4:CustFacade( 6410): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6410): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6410): begin check event
I/AppUp4:CustModeStarterReceiver( 6410): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6410): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6410): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6410): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6410): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  995): Killing 5626:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_10061/pid_5626/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3175): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3175): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3175): networkInfo.isConnected() = false
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  995): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6437 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out(  995): propertyValue:false
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  995): propertyValue:false
I/DSQN    ( 6334): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6334): restart monitoring
I/DSQN    ( 6334): dsqn report finish
D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  995): DSQM DsqnNotification wlan0  1
D/DSQN    (  995): start to monitor internet connection
V/WifiInternetCheck(  995): isHttpConnectionAvailable - We got a valid response : 204
,D/PhoneMonitor( 6437): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6437): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6437): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  995): Killing 6200:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_1000/pid_6200/cgroup.procs: No such file or directory
,V/DownloadManager( 3250): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3250): DownloadService onCreate
,I/NotificationManager( 3250): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3250): in removeSpuriousFiles
V/DownloadManager( 3250): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3250): created cursor android.database.sqlite.SQLiteCursor@1b4bb56c on behalf of 3250
I/CheckinService( 4245): Checkin interval check for package: unspecified last checkin: 1449681133749 min interval config: 0 actual interval: 26238
D/PhoneMonitor( 6437): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6437): [loadFeatureFromXml] *** start feature loading from xml
I/DownloadManager( 3250): in trimDatabase
D/TelephonyAutoProfiling( 6437): [parse] Load xml
V/DownloadManager( 3250): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/TelephonyAutoProfiling( 6437): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6437): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3250): created cursor android.database.sqlite.SQLiteCursor@2e0b5735 on behalf of 3250
D/PhoneMonitor( 6437): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  995): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6469 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3250): DownloadService onStartCommand
I/CheckinService( 4245): Checking schedule, now: 1449681160029 next: 1449681163713
I/CheckinService( 4245): active receiver: disabled
V/DownloadManager( 3250): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3250): created cursor android.database.sqlite.SQLiteCursor@1df4bc58 on behalf of 3250
,V/DownloadManager( 3250): DownloadService onDestroy
,I/ActivityManager(  995): Killing 5967:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5988): android.os.DeadObjectException
,W/System.err( 5988): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5988): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5988): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5988): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5988): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5988): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5988): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5988): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5988): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5988): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5988): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5988): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5988): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5988): android.os.DeadObjectException
W/System.err( 5988): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5988): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5988): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5988): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5988): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5988): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5988): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5988): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5988): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5988): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5988): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5988): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5988): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
E/libprocessgroup(  995): failed to kill 1 processes for processgroup 5967
,D/WeatherAncestor( 2682): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:12:40
W/ActivityManager(  995): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/UpdateThreadPoolManager( 2682): 2 : This is isUpdating : false
D/WeatherAncestor( 2682): connectivity changed - connection : true
D/Weather_cast( 2682): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2682): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:12:40
D/WeatherService( 2682): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  995): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6499 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 25.248ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 23.570ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 25.841ms
,I/ActivityManager(  995): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6524 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  995): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2682): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2682): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2682): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6524): Quickset Services start...
,I/UEI.SmartControl( 6524): Manufacture = LGE
D/UEI.SmartControl( 6524): File observer start...
E/UEI.SmartControl( 6524): IR Port is disabled: false
D/UEI.SmartControl( 6524): Starting file observer...
D/UEI.SmartControl( 6524): Extracting JNI libs...
D/UEI.SmartControl( 6524): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 6499): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6524): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6524): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6524): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6524): --- Selecting new region: 2
I/UEI.SmartControl( 6524): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6524): Platform has CIR...
D/UEI.SmartControl( 6524): NO CIR support, need to check package...
I/UEI.SmartControl( 6524): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6524): QS Service created
E/UEI.SmartControl( 6524): QS start get config
,D/UEI.SmartControl( 6524): Loading JNI Libs...
D/UEI.SmartControl( 6524):  configuring local db...
,I/Babel_SMS( 6499): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6499): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6499): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6499): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6499): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6499): MmsConfig.loadFromResources
E/Babel_SMS( 6499): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6499): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6499): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6499): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6499): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6499): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6499): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6499): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6499): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6499): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6499): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6499): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6499): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6499): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6499): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6499): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6499): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6499): found sensor: Motion Accel, handle=46
,I/art     ( 6499): CheckpointMarkThreadRoots callback created = 0xb042d880
,D/UEI.SmartControl( 6524):  ---- Has DB8: true
,D/UEI.SmartControl( 6524): QS start statue = true Error code = 0
D/UEI.SmartControl( 6524): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6524): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6524): IRRCDataComm has AudioManager!!!!.
I/art     ( 6499): CheckpointMarkThreadRoots callback created = 0xb042d850
W/Settings( 6499): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6499): startup - clean
,W/irrc_jni( 6524): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6524): IrrcClient ++ 
,D/irrcClient( 6524): getIrrcService ++ 
D/irrcClient( 6524): getIrrcService -- 
D/irrcClient( 6524): IrrcClient -- 
W/irrc_jni( 6524): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6524): Services init done
,I/UEI.SmartControl( 6524): Device manager: loading config....
D/UEI.SmartControl( 6524): Config is loaded...
,D/UEI.SmartControl( 6524): QS Service init finished
D/UEI.SmartControl( 6524): QS Service version name: 0.1.73
D/UEI.SmartControl( 6524): QS Service version code: 1073
D/UEI.SmartControl( 6524): Service requested: Control
D/UEI.SmartControl( 6524): -----IControl: 11
D/UEI.SmartControl( 6524): Internal service binding...
D/UEI.SmartControl( 6524): Caller: com.lge.qremote
,I/Babel   ( 6499): deleted: false for 0
D/UEI.SmartControl( 6524): ------------ IControl registerCallback...
I/UEI.SmartControl( 6524): Registering callback...
D/UEI.SmartControl( 6524): -----IControl: 19
D/UEI.SmartControl( 6524): Caller: com.lge.qremote
I/UEI.SmartControl( 6524): Registering Services Ready callback...
I/UEI.SmartControl( 6524): Notify client services are ready...
,D/UEI.SmartControl( 6524): -----IControl: 8
D/UEI.SmartControl( 6524): Caller: com.lge.qremote
D/UEI.SmartControl( 6524):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6524): Notify AllClients services are ready: 0
,I/ActivityManager(  995): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6565 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  995): Killing 6225:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_1000/pid_6225/cgroup.procs: No such file or directory
,W/AudioCapabilities( 6499): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6499): Unsupported mime audio/adpcm
W/AudioCapabilities( 6499): Unsupported mime audio/g726
W/AudioCapabilities( 6499): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6499): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6499): Unsupported mime video/mjpg
,W/VideoCapabilities( 6499): Unsupported mime video/theora
W/AudioCapabilities( 6499): Unsupported mime audio/evrc
,W/AudioCapabilities( 6499): Unsupported mime audio/qcelp
W/VideoCapabilities( 6499): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6499): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6499): Unsupported mime audio/qcelp
W/AudioCapabilities( 6499): Unsupported mime audio/evrc
,W/VideoCapabilities( 6499): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6499): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6499): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6499): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6499): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6499): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  995): Process com.google.android.music:main (pid 6308) has died
,I/vclib   ( 6499): onServiceConnected
W/Babel   ( 6499): Attempted to change video mute state without an active call.
D/libc-netbsd( 6499): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6499): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6499): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6499): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6499): propertyValue:false
I/NotificationManager( 6499): com.google.android.talk: cancel(10436) by com.google.android.talk
I/Babel   ( 6499): connection state changed from UNKNOWN to CONNECTED
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6565): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6565): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6565): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6565): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6565): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6565):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6565):   adb logcat -s GAv4
W/GAv4    ( 6565): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6565): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6565): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/WebViewFactory( 6565): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6565): Time to load native libraries: 2 ms (timestamps 8917-8919)
,I/LibraryLoader( 6565): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6565): Binding Chromium to main looper Looper (main, tid 1) {37f2677a}
I/LibraryLoader( 6565): Expected native library version number "",actual native library version number ""
I/chromium( 6565): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6565): Initializing chromium process, singleProcess=true
W/art     ( 6565): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6565): ApplicationContext is null in ApplicationStatus
,W/chromium( 6565): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6565): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6565): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6565): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6565): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6565): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6565): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6565): Remote Branch: 
I/Adreno-EGL( 6565): Local Patches: 
I/Adreno-EGL( 6565): Reconstruct Branch: 
I/NSApplication( 6565): Starting up...
V/AudioPolicyService(  278): registerClient() client 0xb40274e0, uid 10079
W/AudioManagerAndroid( 6565): Requires BLUETOOTH permission
,I/ActivityManager(  995): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6628 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  995): Killing 5988:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10106/pid_5988/cgroup.procs: No such file or directory
,I/ActivityManager(  995): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6648 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  995): Killing 6352:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_10021/pid_6352/cgroup.procs: No such file or directory
,W/ResourcesManager( 6648): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{1591f3b2 type 2 when 109717 com.google.android.gms} when 109717
,I/ActivityManager(  995): Killing 6385:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_1000/pid_6385/cgroup.procs: No such file or directory
,I/ActivityManager(  995): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6675 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  995): RTC_WAKEUP set : Alarm{26edb85f type 0 when 1449681163626 com.google.android.googlequicksearchbox} when 1449681163626
,I/MusicStore( 6675): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6675): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6675): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6675): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/art     (  995): Explicit concurrent mark sweep GC freed 24778(1291KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3ms total 146.232ms
,W/ResourcesManager( 6675): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6675): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6675): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6675): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6675): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b8830cd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6675): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6675): GMSCore installation verified
,I/ConfigStore( 6675): Config Database version: 1
,I/MediaRouter( 6675): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6675): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6675): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6675): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  995): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6711 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6675): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6675): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6711): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6711): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6711): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  995): Killing 6410:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10011/pid_6410/cgroup.procs: No such file or directory
,I/NotificationManager( 6675): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6711): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6711): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6711): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  995): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6743 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,V/AlarmManager(  995): RTC_WAKEUP set : Alarm{2bccdb6c type 0 when 1449681163713 com.google.android.gms} when 1449681163713
,I/HubEmail( 6711): JNI_OnLoad()
I/HubEmail( 6711): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6711): registerNatives()
I/HubEmail( 6711): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6711): registerNativeMethods()
I/HubEmail( 6711): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6711): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  995): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6761 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  995): RTC_WAKEUP set : Alarm{39390dca type 0 when 1449681165246 com.android.vending} when 1449681165246
,W/Settings( 6711): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  995): Killing 6437:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10038/pid_6437/cgroup.procs: No such file or directory
,D/LGDMClient( 6743): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6743): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6743): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6743): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  995): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6779 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 6743): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6743): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6743): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6743): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6743): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6743): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6743): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6743): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6743): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6743): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  995): Killing 6469:com.lge.drmservice/u0a51 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6779): onCreate
,W/AppUp4:DB( 6779):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6779):  setFingerPrint start
I/AppUp4:DB( 6779):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6779):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6779):  SDK version = 0
I/AppUp4:DB( 6779):  beforefinger == newfinger no write in DB
W/libprocessgroup(  995): failed to open /acct/uid_10051/pid_6469/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6779): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6779): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6779): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6779): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6779): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6779): onReceive
I/AppUp4:CustModeStarterReceiver( 6779): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6779): Context : android.app.ReceiverRestrictedContext@236e7361
D/AppUp4:CustFacade( 6779): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6779): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6779): begin check event
I/AppUp4:CustModeStarterReceiver( 6779): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6779): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6779): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6779): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6779): handleAsyncCustNotification do not startCustService
I/LgeMiscReceiver( 3175): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3175): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3175): networkInfo.isConnected() = false
,I/ActivityManager(  995): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6811 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/Finsky  ( 6761): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/PhoneMonitor( 6811): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6811): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6811): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  995): Killing 6524:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_10089/pid_6524/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6811): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6811): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6811): [parse] Load xml
I/CheckinService( 4245): Checkin interval check for package: unspecified last checkin: 1449681133749 min interval config: 0 actual interval: 32571
V/TelephonyAutoProfiling( 6811): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6811): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/DownloadManager( 3250): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/PhoneMonitor( 6811): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3250): DownloadService onCreate
I/DownloadManager( 3250): in removeSpuriousFiles
I/NotificationManager( 3250): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3250): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3250): created cursor android.database.sqlite.SQLiteCursor@363a4696 on behalf of 3250
D/Finsky  ( 6761): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/DownloadManager( 3250): in trimDatabase
V/DownloadManager( 3250): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,W/Settings( 6761): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  995): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6854 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3250): DownloadService onStartCommand
I/CheckinService( 4245): Checking schedule, now: 1449681166389 next: 1449681163713
I/CheckinService( 4245): active receiver: enabled
W/Settings( 6761): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
V/DownloadManager( 3250): created cursor android.database.sqlite.SQLiteCursor@14c37ed on behalf of 3250
I/art     (  310): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 350us total 23.966ms
,V/DownloadManager( 3250): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/NotificationManager( 6761): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3250): created cursor android.database.sqlite.SQLiteCursor@34cc3622 on behalf of 3250
I/art     (  310): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 24.918ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 22.111ms
,I/CheckinService( 4245): Preparing to send checkin request
I/EventLogService( 4245): Accumulating logs since 1449681125435
,V/DownloadManager( 3250): DownloadService onDestroy
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/Ads     ( 6761): Skipping gmscore version check
,D/Finsky  ( 6761): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6761): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3250): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3250): created cursor android.database.sqlite.SQLiteCursor@19b2be70 on behalf of 6761
I/CheckinRequestBuilder( 4245): Checkin reason type: 8 attempt count: 1
D/Finsky  ( 6761): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/ActivityThread( 4245): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager(  995): Killing 6499:com.google.android.talk/u0a61 (adj 15): empty #11
D/Finsky  ( 6761): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/WeatherAncestor( 2682): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:12:46
,W/libprocessgroup(  995): failed to open /acct/uid_10061/pid_6499/cgroup.procs: No such file or directory
D/UpdateThreadPoolManager( 2682): 2 : This is isUpdating : false
D/WeatherAncestor( 2682): connectivity changed - connection : true
D/Weather_cast( 2682): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2682): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:12:46
D/WeatherService( 2682): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/Finsky  ( 6761): [830] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6761): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  995): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6882 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  995): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2682): 2 : Utils getTopActivity com.lge.launcher2 / true
I/jxcore-log( 6055): Test app app.js loaded
I/jxcore-log( 6055): 
,D/WeatherService( 2682): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2682): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/ActivityManager(  995): Killing 6565:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/chromium( 6055): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup(  995): failed to open /acct/uid_10079/pid_6565/cgroup.procs: No such file or directory
W/ResourcesManager( 6882): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  995): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6901 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/Babel_SMS( 6882): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6882): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6882): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6882): MmsConfig.loadFromDatabase
W/ResourcesManager( 6901): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6901): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Babel_SMS( 6882): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6882): MmsConfig.loadFromResources
E/Babel_SMS( 6882): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6882): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6882): CheckpointMarkThreadRoots callback created = 0xb042d870
,I/art     ( 6882): CheckpointMarkThreadRoots callback created = 0xb042d850
,I/MultiDex( 6901): VM with version 2.1.0 has multidex support
I/MultiDex( 6901): install
I/MultiDex( 6901): VM has multidex support, MultiDex support library is disabled.
,D/SensorManager( 6882): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6882): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6882): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6882): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6882): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6882): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6882): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6882): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6882): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6882): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6882): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6882): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6882): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6882): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6882): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6882): found sensor: Motion Accel, handle=46
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/JNIHelp ( 6901): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Settings( 6882): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6882): startup - clean
I/Babel   ( 6882): deleted: false for 0
,W/ActivityThread( 6901): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6901): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@376477ca: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6901): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  995): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6928 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager( 6901): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6901): com.google.android.gms: cancel(39789) by com.google.android.gms
W/AudioCapabilities( 6882): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6882): Unsupported mime audio/adpcm
W/AudioCapabilities( 6882): Unsupported mime audio/g726
W/AudioCapabilities( 6882): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6882): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6882): Unsupported mime video/mjpg
,W/VideoCapabilities( 6882): Unsupported mime video/theora
,W/AudioCapabilities( 6882): Unsupported mime audio/evrc
,W/AudioCapabilities( 6882): Unsupported mime audio/qcelp
W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
I/art     ( 6901): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6901): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/AudioCapabilities( 6882): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6882): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6882): Unsupported mime audio/evrc
W/VideoCapabilities( 6882): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6882): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6882): onServiceConnected
W/Babel   ( 6882): Attempted to change video mute state without an active call.
,I/NotificationManager( 6882): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6882): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6882): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6882): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6882): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6882): propertyValue:false
I/Babel   ( 6882): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  995): Killing 6628:com.android.chrome/u0a48 (adj 15): empty #11
,D/NativeLibraryUtils( 6901): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  995): failed to open /acct/uid_10048/pid_6628/cgroup.procs: No such file or directory
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6928): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6928): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/WVCdm   (  278): Instantiating CDM.
I/WVCdm   (  278): CdmEngine::OpenSession
I/WVCdm   (  278): Level3 Library Dec 11 2014 16:13:16
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6928): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6928): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6928): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6928):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6928):   adb logcat -s GAv4
W/WVCdm   (  278): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  278): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  278): L1 library not specified. Falling Back to L3
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=466534475
I/ActivityManager(  995): Process com.google.android.music:main (pid 6675) has died
,W/GAv4    ( 6928): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/art     (  995): Explicit concurrent mark sweep GC freed 21316(997KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.385ms total 167.106ms
W/GAv4    ( 6928): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6928): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6928): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6928): Time to load native libraries: 1 ms (timestamps 5210-5211)
,I/LibraryLoader( 6928): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6928): Binding Chromium to main looper Looper (main, tid 1) {37f2677a}
I/LibraryLoader( 6928): Expected native library version number "",actual native library version number ""
I/chromium( 6928): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6928): Initializing chromium process, singleProcess=true
,W/art     ( 6928): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6928): ApplicationContext is null in ApplicationStatus
W/chromium( 6928): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6928): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6928): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6928): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6928): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6928): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6928): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6928): Remote Branch: 
I/Adreno-EGL( 6928): Local Patches: 
I/Adreno-EGL( 6928): Reconstruct Branch: 
D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 115301870741; DSPS: 3876891; Offset : -3022712059
,V/AudioPolicyService(  278): registerClient() client 0xb57ea400, uid 10079
,W/AudioManagerAndroid( 6928): Requires BLUETOOTH permission
I/NSApplication( 6928): Starting up...
I/art     ( 6901): CheckpointMarkThreadRoots callback created = 0xaaf0a580
,I/ActivityManager(  995): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6991 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6901): CheckpointMarkThreadRoots callback created = 0xaaf0a570
,I/ActivityManager(  995): Killing 6711:com.lge.email/u0a21 (adj 15): empty #11
,I/WVCdm   (  278): CdmEngine::OpenSession
,W/libprocessgroup(  995): failed to open /acct/uid_10021/pid_6711/cgroup.procs: No such file or directory
,I/ActivityManager(  995): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7015 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7015): Database version: 120
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7015): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7015): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7015): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7015): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7015): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7015): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7015): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7015): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b8830cd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7015): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7015): GMSCore installation verified
I/ConfigStore( 7015): Config Database version: 1
,I/art     ( 1915): Explicit concurrent mark sweep GC freed 2169(81KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 390us total 36.468ms
,I/MediaRouter( 7015): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7015): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7015): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7015): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  995): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7044 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  995): Process com.lge.appbox.client (pid 6779) has died
,I/GHttpClientFactory( 7015): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7015): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7044): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7044): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7044): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationManager( 7015): com.google.android.music: cancel(1061) by com.google.android.music
,I/WVCdm   (  278): CdmEngine::CloseSession
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=1249646682
I/LGEmail ( 7044): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7044): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/eas_req ( 7044): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 6743): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6743): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6743): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6743): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6743): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6743): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 6743): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6743): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/HubEmail( 7044): JNI_OnLoad()
,I/HubEmail( 7044): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7044): registerNatives()
I/HubEmail( 7044): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7044): registerNativeMethods()
I/HubEmail( 7044): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7044): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  995): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7072 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/Settings( 7044): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 6743): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6743): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6743): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6743): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6743): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6743): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  995): Killing 6811:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10038/pid_6811/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7072): onCreate
,W/AppUp4:DB( 7072):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7072):  setFingerPrint start
I/AppUp4:DB( 7072):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7072):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7072):  SDK version = 0
I/AppUp4:DB( 7072):  beforefinger == newfinger no write in DB
I/ActivityManager(  995): Process com.google.android.apps.magazines (pid 6928) has died
,D/AppUp4:AppBoxApplication( 7072): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7072): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7072): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7072): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7072): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7072): onReceive
I/AppUp4:CustModeStarterReceiver( 7072): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7072): Context : android.app.ReceiverRestrictedContext@236e7361
D/AppUp4:CustFacade( 7072): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7072): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7072): begin check event
I/AppUp4:CustModeStarterReceiver( 7072): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 7072): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7072): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7072): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7072): handleAsyncCustNotification do not startCustService
I/LgeMiscReceiver( 3175): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3175): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3175): networkInfo.isConnected() = true
D/PhoneState( 3175): setPdpRejectCasuse : false
I/ActivityManager(  995): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7091 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/MusicWidget( 2614): mDelayedStopHandler : unbind
,I/MusicBrowser( 2692): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2692): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2692): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2692): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2692): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2692): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2692): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  995):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@134e0c37com.lge.music.MediaPlaybackService$6@297e25a4
,D/MusicBrowser( 2692): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1e3de49d
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
,I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2692): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/PhoneMonitor( 7091): Register our PhoneStateListener
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2692): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2692): reset
,D/MobileConnectivityChangeReceiver( 7091): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7091): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  995): Killing 6854:com.lge.drmservice/u0a51 (adj 15): empty #11
V/MediaPlayer[Native]( 2692): setListener
V/MediaPlayer[Native]( 2692): disconnect
V/MediaPlayer[Native]( 2692): destructor
V/AudioFlinger(  278): releasing 19 from 2692 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/MediaPlayer[Native]( 2692): disconnect
D/PhoneMonitor( 7091): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/MusicBrowser( 2692): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
V/TelephonyAutoProfiling( 7091): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7091): [parse] Load xml
V/TelephonyAutoProfiling( 7091): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7091): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/SmartShareClient( 2692): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2692): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2692): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
,I/MusicBrowser( 2692): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2692): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2692): [SmartShareManagerClient] unregisterListener: 453390093
W/SmartShareClient( 2692): [SmartShareManagerClient] unregisterListener invalid listener: 453390093
I/SmartShareClient( 2692): [SmartShareManagerClient] terminate service: 2692/MediaPlaybackService/652532587
D/PhoneMonitor( 7091): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
E/HomeCloudIF( 2692): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2692): [SmartShareManagerClient] unbindService context:android.app.Application@15062ec2
W/libprocessgroup(  995): failed to open /acct/uid_10051/pid_6854/cgroup.procs: No such file or directory
V/DownloadManager( 3250): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3250): DownloadService onCreate
I/DownloadManager( 3250): in removeSpuriousFiles
I/NotificationManager( 3250): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/CloudHub( 2692): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2692): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
V/DownloadManager( 3250): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/CloudHub( 2692): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
V/DownloadManager( 3250): created cursor android.database.sqlite.SQLiteCursor@21c165e9 on behalf of 3250
I/MusicBrowser( 2692): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2692): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/DownloadManager( 3250): in trimDatabase
,V/DownloadManager( 3250): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3250): created cursor android.database.sqlite.SQLiteCursor@79b926e on behalf of 3250
I/ActivityManager(  995): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7113 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3250): DownloadService onStartCommand
I/CloudHub( 2692): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29973
I/CheckinService( 4245): Checkin interval check for package: unspecified last checkin: 1449681133749 min interval config: 0 actual interval: 37767
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
V/DownloadManager( 3250): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  995): Killing 6761:com.android.vending/u0a36 (adj 15): empty #11
V/DownloadManager( 3250): created cursor android.database.sqlite.SQLiteCursor@74177a5 on behalf of 3250
,W/libprocessgroup(  995): failed to open /acct/uid_10036/pid_6761/cgroup.procs: No such file or directory
,V/DownloadManager( 3250): DownloadService onDestroy
I/ActivityManager(  995): Killing 6882:com.google.android.talk/u0a61 (adj 15): empty #11
,D/WeatherAncestor( 2682): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:12:51
,W/libprocessgroup(  995): failed to open /acct/uid_10061/pid_6882/cgroup.procs: No such file or directory
,D/UpdateThreadPoolManager( 2682): 2 : This is isUpdating : false
D/WeatherAncestor( 2682): connectivity changed - connection : true
D/Weather_cast( 2682): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2682): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:12:51
,D/WeatherService( 2682): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  995): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7130 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  995): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2682): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2682): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2682): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7130): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/Babel_SMS( 7130): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7130): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7130): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7130): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7130): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7130): MmsConfig.loadFromResources
E/Babel_SMS( 7130): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7130): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7130): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7130): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7130): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7130): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7130): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7130): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7130): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7130): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7130): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7130): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7130): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7130): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7130): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7130): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7130): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7130): found sensor: Motion Accel, handle=46
W/Settings( 7130): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     ( 7130): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,I/Babel_Crash( 7130): startup - clean
I/Babel   ( 7130): deleted: false for 0
,I/art     ( 7130): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/ActivityManager(  995): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7161 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.382ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.247ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 25.366ms
,I/WVCdm   (  278): CdmEngine::CloseSession
I/WVCdm   (  278): L3 Terminate.
W/AudioCapabilities( 7130): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7130): Unsupported mime audio/adpcm
,W/AudioCapabilities( 7130): Unsupported mime audio/g726
W/AudioCapabilities( 7130): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7130): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7130): Unsupported mime video/mjpg
W/VideoCapabilities( 7130): Unsupported mime video/theora
,W/AudioCapabilities( 7130): Unsupported mime audio/evrc
,W/AudioCapabilities( 7130): Unsupported mime audio/qcelp
W/VideoCapabilities( 7130): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7130): Unsupported mime audio/amr-wb-plus
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/AudioCapabilities( 7130): Unsupported mime audio/qcelp
W/AudioCapabilities( 7130): Unsupported mime audio/evrc
,W/VideoCapabilities( 7130): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7130): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7130): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7130): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7130): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7130): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7130): onServiceConnected
W/Babel   ( 7130): Attempted to change video mute state without an active call.
,I/dex2oat ( 7180): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7161): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/libc-netbsd( 7130): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7130): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7130): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7130): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,W/ContextImpl( 7161): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/System.out( 7130): propertyValue:false
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7161): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/NotificationManager( 7130): com.google.android.talk: cancel(10436) by com.google.android.talk
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7161): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7161): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7161):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7161):   adb logcat -s GAv4
,I/Babel   ( 7130): connection state changed from UNKNOWN to CONNECTED
,W/GAv4    ( 7161): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  995): Killing 6991:com.android.chrome/u0a48 (adj 15): empty #11
W/GAv4    ( 7161): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7161): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  995): failed to open /acct/uid_10048/pid_6991/cgroup.procs: No such file or directory
,I/dex2oat ( 7180): dex2oat took 158.489ms (threads: 4)
I/Adreno-EGL( 6901): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6901): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6901): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6901): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6901): Remote Branch: 
I/Adreno-EGL( 6901): Local Patches: 
I/Adreno-EGL( 6901): Reconstruct Branch: 
,I/WebViewFactory( 7161): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7161): Time to load native libraries: 2 ms (timestamps 9632-9634)
I/LibraryLoader( 7161): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7161): Binding Chromium to main looper Looper (main, tid 1) {37f2677a}
I/LibraryLoader( 7161): Expected native library version number "",actual native library version number ""
I/chromium( 7161): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7161): Initializing chromium process, singleProcess=true
,W/art     ( 7161): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7161): ApplicationContext is null in ApplicationStatus
W/chromium( 7161): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7161): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7161): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7161): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7161): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7161): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7161): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7161): Remote Branch: 
I/Adreno-EGL( 7161): Local Patches: 
I/Adreno-EGL( 7161): Reconstruct Branch: 
I/Adreno-EGL( 6901): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6901): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6901): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6901): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6901): Remote Branch: 
I/Adreno-EGL( 6901): Local Patches: 
I/Adreno-EGL( 6901): Reconstruct Branch: 
,I/art     ( 6648): CheckpointMarkThreadRoots callback created = 0xb042de40
,I/art     ( 6648): CheckpointMarkThreadRoots callback created = 0xb042de30
V/AudioPolicyService(  278): registerClient() client 0xb57ea440, uid 10079
,W/AudioManagerAndroid( 7161): Requires BLUETOOTH permission
I/Adreno-EGL( 6901): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6901): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6901): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6901): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6901): Remote Branch: 
I/Adreno-EGL( 6901): Local Patches: 
I/Adreno-EGL( 6901): Reconstruct Branch: 
,I/NSApplication( 7161): Starting up...
I/ActivityManager(  995): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7230 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  995): Killing 6648:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_10086/pid_6648/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 4245): Classify the device as Phone.
,I/art     (  995): Explicit concurrent mark sweep GC freed 16034(758KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.587ms total 148.638ms
,I/ActivityManager(  995): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7254 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  995): Killing 7015:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_10081/pid_7015/cgroup.procs: No such file or directory
,D/libc-netbsd( 4245): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4245): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4245): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4245): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
,W/ResourcesManager( 7254): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 4245): propertyValue:false
,D/libc-netbsd( 4245): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4245): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4245): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4245): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4245): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4245): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4245): Sending checkin request (9732 bytes)
,I/ActivityManager(  995): Killing 7044:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10021/pid_7044/cgroup.procs: No such file or directory
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  995): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7283 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7283): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 4245): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4245): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BluetoothManagerService(  995): Message: 20
D/BluetoothManagerService(  995): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16f613f:true
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BluetoothAdapterService(657717108)( 1991): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d367c6a
,D/BluetoothAdapterService(657717108)( 1991): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d367c6a
I/CheckinRequestBuilder( 4245): Classify the device as Phone.
,I/CheckinTask( 4245): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/ActivityManager(  995): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7308 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/CheckinService( 4245): Checking schedule, now: 1449681174322 next: 1450208423279
,I/CheckinService( 4245): active receiver: disabled
,V/LGMDMManager( 7283): Create singleton instance
,I/CheckinService( 4245): Checking schedule, now: 1449681174370 next: 1450208423279
I/CheckinService( 4245): active receiver: disabled
D/CheckinService( 4245): Recording last checkin time for package unspecified as 1449681174382
,I/ActivityManager(  995): Killing 7072:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/UEI.SmartControl( 7308): Quickset Services start...
,I/UEI.SmartControl( 7308): Manufacture = LGE
D/UEI.SmartControl( 7308): File observer start...
E/UEI.SmartControl( 7308): IR Port is disabled: false
D/UEI.SmartControl( 7308): Starting file observer...
D/UEI.SmartControl( 7308): Extracting JNI libs...
D/UEI.SmartControl( 7308): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  995): Killing 6743:com.lge.lgdmsclient/1000 (adj 15): empty #12
,I/AudioManager( 7283): getMode name:com.lge.qremote
,W/libprocessgroup(  995): failed to open /acct/uid_10011/pid_7072/cgroup.procs: No such file or directory
W/libprocessgroup(  995): failed to open /acct/uid_1000/pid_6743/cgroup.procs: No such file or directory
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/CheckinService( 4245): Checkin interval check for package: unspecified last checkin: 1449681174382 min interval config: 0 actual interval: 109
,I/CheckinService( 4245): Checking schedule, now: 1449681174502 next: 1450208423279
I/CheckinService( 4245): active receiver: disabled
D/WearableService( 1734): callingUid 10006, callindPid: 1734
,W/ContextImpl( 3618): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
D/LocationInitializer( 4245): Restart initialization of location
,E/MDM     ( 1734): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 1734): propertyValue:false
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
,V/SetupWizard( 7091): Connected to Gservices successfully
I/AudioManager( 7283): getMode name:com.lge.qremote
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/AudioFlinger(  278): 2692 died, releasing its sessions
V/AudioFlinger(  278):  pid 1753 @ 0
V/AudioFlinger(  278):  pid 3175 @ 1
V/AudioFlinger(  278):  pid 3175 @ 2
I/ActivityManager(  995): Process com.lge.music (pid 2692) has died
,D/UEI.SmartControl( 7308): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7308): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7308): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7308): --- Selecting new region: 2
I/UEI.SmartControl( 7308): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7308): Platform has CIR...
,D/UEI.SmartControl( 7308): NO CIR support, need to check package...
I/UEI.SmartControl( 7308): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 7308): QS Service created
,E/UEI.SmartControl( 7308): QS start get config
,D/UEI.SmartControl( 7308): Loading JNI Libs...
,D/UEI.SmartControl( 7308):  configuring local db...
D/UEI.SmartControl( 7308):  ---- Has DB8: true
,D/UEI.SmartControl( 7308): QS start statue = true Error code = 0
D/UEI.SmartControl( 7308): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 7308): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7308): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7308): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7308): IrrcClient ++ 
D/irrcClient( 7308): getIrrcService ++ 
,D/irrcClient( 7308): getIrrcService -- 
D/irrcClient( 7308): IrrcClient -- 
W/irrc_jni( 7308): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7308): Services init done
I/UEI.SmartControl( 7308): Device manager: loading config....
D/UEI.SmartControl( 7308): QS Service init finished
,D/UEI.SmartControl( 7308): QS Service version name: 0.1.73
D/UEI.SmartControl( 7308): QS Service version code: 1073
D/UEI.SmartControl( 7308): Service requested: Control
D/UEI.SmartControl( 7308): Config is loaded...
D/UEI.SmartControl( 7308):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7308): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7308): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7308): Internal service binding...
D/UEI.SmartControl( 7308): -----IControl: 11
D/UEI.SmartControl( 7308): Caller: com.lge.qremote
D/UEI.SmartControl( 7308): ------------ IControl registerCallback...
I/UEI.SmartControl( 7308): Registering callback...
D/UEI.SmartControl( 7308): -----IControl: 19
,D/UEI.SmartControl( 7308): Caller: com.lge.qremote
I/UEI.SmartControl( 7308): Registering Services Ready callback...
I/UEI.SmartControl( 7308): Notify client services are ready...
D/UEI.SmartControl( 7308): -----IControl: 8
D/UEI.SmartControl( 7308): Caller: com.lge.qremote
I/AudioManager( 7283): getMode name:com.lge.qremote
,I/AudioManager( 7283): getMode name:com.lge.qremote
,I/AudioManager( 7283): getMode name:com.lge.qremote
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1841): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  995): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/ActivityManager(  995): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7373 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  995): Handling package changes for user 0
,I/NotificationManager( 7130): com.google.android.talk: cancel(8) by com.google.android.talk
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7130): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7130): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AppUp4:AppBoxCP( 7373): onCreate
,W/AppUp4:DB( 7373):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7373):  setFingerPrint start
I/AppUp4:DB( 7373):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7373):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7373):  SDK version = 0
I/AppUp4:DB( 7373):  beforefinger == newfinger no write in DB
V/JNIHelp ( 7130): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AppUp4:AppBoxApplication( 7373): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7373): onReceive
I/AppUp4:CustModeStarterReceiver( 7373): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7373): Context : android.app.ReceiverRestrictedContext@348070ba
D/AppUp4:CustFacade( 7373): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7373): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7373): begin check event
I/AppUp4:CustModeStarterReceiver( 7373): Event For Nothing, skip.
,I/ActivityManager(  995): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7397 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/NotificationService(  995): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  995): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  995): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  995): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  995): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  995): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@345bcedf
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
,W/ResourcesManager(  995): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/LCardEmulationManager( 1787): getDefaultRoute
W/ResourcesManager( 7397): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7397): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7397): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,W/System  ( 7130): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7130): Installed default security provider GmsCore_OpenSSL
W/ResourceType(  995): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/AppConfig( 7397): Total System Memory = 906309632
,I/GalleryUtils( 7397): Application Heap = 96 MB
,I/AppConfig( 7397): App Tier : NOT_DEF
,D/SystemHelper( 7397): region [EU], country [EU], operator [OPEN], sub-operator []
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  995): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7421 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/LocationProviderProxy(  995): applying state to connected service
,W/ResourcesManager( 7421): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7421): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7421): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7421): BUILD Country: EU
I/SystemConfig( 7421): BUILD Operator: OPEN
,I/ActivityManager(  995): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7440 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  995): Killing 7113:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_10051/pid_7113/cgroup.procs: No such file or directory
,I/SystemConfig( 7421): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7421): existFile = false
I/SystemConfig( 7421): canReadFile = false
I/SystemConfig( 7421): systemFeature RCS result false
D/SystemConfig( 7421): refreshRcsSupport() :false
I/LockScreenSettings( 7440): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7440): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7440): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7440): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7440): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7440): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1964): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  995): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7464 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  995): Killing 7161:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/art     ( 7254): CheckpointMarkThreadRoots callback created = 0xb042dfa0
,I/art     ( 7254): CheckpointMarkThreadRoots callback created = 0xb042df80
,I/UpdateIcingCorporaServi( 1964): UpdateCorporaTask done [took 115 ms] updated apps [took 115 ms] 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  995): failed to open /acct/uid_10079/pid_7161/cgroup.procs: No such file or directory
,I/art     (  995): Explicit concurrent mark sweep GC freed 23717(1232KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 1.856ms total 149.151ms
,I/ActivityManager(  995): Killing 7230:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10048/pid_7230/cgroup.procs: No such file or directory
,V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{2dcb0478 type 2 when 124952 com.google.android.gms} when 124952
D/Finsky  ( 7464): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7464): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7464): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7464): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7464): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3250): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3250): created cursor android.database.sqlite.SQLiteCursor@30196b2b on behalf of 7464
D/Ads     ( 7464): Skipping gmscore version check
I/ActivityManager(  995): Killing 7091:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,D/Finsky  ( 7464): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7464): [1] Libraries$2.run: Finished loading 1 libraries.
W/libprocessgroup(  995): failed to open /acct/uid_10038/pid_7091/cgroup.procs: No such file or directory
,D/Finsky  ( 7464): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4245): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4245): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7464): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4245): updateResources: need to parse f{com.google.android.gms}
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Icing   ( 4245): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/PowerManagerServiceEx(  995): acquireWakeLockInternal: lock=1051057766, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=995
,D/WeatherService( 2682): 2 : TimeTick Intent has been received, Time(hour:min:sec) 18:13:0
,D/WeatherService( 2682): 2 : TimeTick Intent And Screen On
D/WeatherService( 2682): 2 : SDK version : 21
W/ActivityManager(  995): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2682): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2682): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2682): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2682): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2682): 2 : This is isUpdating : false
D/WeatherService( 2682): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2682): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2682): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2682): 2 : Fixed theme : optimus
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,D/WeatherReflect( 2682): 2 : Map key string is -2
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,D/lim     ( 2682): 2 : time = 18:13
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/WeatherReflect( 2682): Model Name : LG-D722
D/WeatherTheme( 2682): 2 : Different view - status_min_formatted : 12 != 13
D/WeatherTheme( 2682): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2682): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2682): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2682): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2682): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2682): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/Weather4x2_optimus( 2682): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2682): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2682): forecast size is 0
D/Theme   ( 2682): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2682): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2682): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2682): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2682): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2682): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2682): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2682): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2682): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2682): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2682): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2682): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2682): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2682): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2682): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2682): url is : null
D/Theme   ( 2682): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2682): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2682): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2682): 2 : update view, appWidgetId: 2
D/WeatherService( 2682): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 18:13:0
D/PowerManagerServiceEx(  995): releaseWakeLockInternal: lock=1051057766 [*alarm*], flags=0x0
,D/UEI.SmartControl( 7308): Internal timer expired: 1
,I/Icing   ( 4245): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  995): Killing 7373:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/libprocessgroup(  995): failed to open /acct/uid_10011/pid_7373/cgroup.procs: No such file or directory
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1991): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  995): Killing 7130:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10061/pid_7130/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 135303085160; DSPS: 4532291; Offset : -3022718395
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{1f46f5a7 type 2 when 145300 com.google.android.gms} when 145300
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 35305(2MB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 13MB/22MB, paused 1.520ms total 100.656ms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1734): Vacuum at: now=1449681199085 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  995): ALS enabled for SRE
,D/PowerManagerServiceEx(  995): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29084 ms ago)
D/qdlights(  995): set_light_backlight: 252
,D/qdlights(  995): set_light_backlight: 249
D/qdlights(  995): set_light_backlight: 246
,D/qdlights(  995): set_light_backlight: 242
,D/qdlights(  995): set_light_backlight: 239
,D/qdlights(  995): set_light_backlight: 236
,D/qdlights(  995): set_light_backlight: 232
,D/qdlights(  995): set_light_backlight: 229
,D/qdlights(  995): set_light_backlight: 226
,D/qdlights(  995): set_light_backlight: 222
,D/qdlights(  995): set_light_backlight: 219
,D/qdlights(  995): set_light_backlight: 216
,D/qdlights(  995): set_light_backlight: 212
,D/qdlights(  995): set_light_backlight: 209
,D/qdlights(  995): set_light_backlight: 206
,D/qdlights(  995): set_light_backlight: 202
,D/qdlights(  995): set_light_backlight: 199
,D/qdlights(  995): set_light_backlight: 196
,D/qdlights(  995): set_light_backlight: 192
,D/qdlights(  995): set_light_backlight: 189
,D/qdlights(  995): set_light_backlight: 186
,D/qdlights(  995): set_light_backlight: 182
,D/qdlights(  995): set_light_backlight: 179
,D/qdlights(  995): set_light_backlight: 176
,D/qdlights(  995): set_light_backlight: 172
,D/qdlights(  995): set_light_backlight: 169
,D/qdlights(  995): set_light_backlight: 166
,D/qdlights(  995): set_light_backlight: 162
,D/qdlights(  995): set_light_backlight: 159
,D/qdlights(  995): set_light_backlight: 156
,D/qdlights(  995): set_light_backlight: 152
,D/qdlights(  995): set_light_backlight: 149
,D/qdlights(  995): set_light_backlight: 146
,D/qdlights(  995): set_light_backlight: 142
,D/qdlights(  995): set_light_backlight: 139
,D/qdlights(  995): set_light_backlight: 136
,D/qdlights(  995): set_light_backlight: 129
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  995): set_light_backlight: 126
,D/qdlights(  995): set_light_backlight: 122
,D/qdlights(  995): set_light_backlight: 119
,D/qdlights(  995): set_light_backlight: 116
,D/qdlights(  995): set_light_backlight: 112
,D/qdlights(  995): set_light_backlight: 109
,D/qdlights(  995): set_light_backlight: 106
,D/qdlights(  995): set_light_backlight: 102
,D/qdlights(  995): set_light_backlight: 99
,D/qdlights(  995): set_light_backlight: 96
,D/qdlights(  995): set_light_backlight: 92
,D/qdlights(  995): set_light_backlight: 89
,D/qdlights(  995): set_light_backlight: 86
,D/qdlights(  995): set_light_backlight: 82
,D/qdlights(  995): set_light_backlight: 79
,D/qdlights(  995): set_light_backlight: 76
,D/qdlights(  995): set_light_backlight: 72
,D/qdlights(  995): set_light_backlight: 69
,D/qdlights(  995): set_light_backlight: 66
,D/qdlights(  995): set_light_backlight: 62
,D/qdlights(  995): set_light_backlight: 59
,D/qdlights(  995): set_light_backlight: 56
,D/qdlights(  995): set_light_backlight: 52
,D/qdlights(  995): set_light_backlight: 49
,D/qdlights(  995): set_light_backlight: 46
,D/qdlights(  995): set_light_backlight: 42
,D/qdlights(  995): set_light_backlight: 39
,D/qdlights(  995): set_light_backlight: 36
,D/qdlights(  995): set_light_backlight: 32
,D/qdlights(  995): set_light_backlight: 29
,D/qdlights(  995): set_light_backlight: 26
,D/qdlights(  995): set_light_backlight: 22
,D/qdlights(  995): set_light_backlight: 19
,D/qdlights(  995): set_light_backlight: 16
,D/qdlights(  995): set_light_backlight: 12
,D/qdlights(  995): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 155303758643; DSPS: 5187673; Offset : -3022716715
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  995): ALS enabled for SRE
D/PowerManagerServiceEx(  995): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36080 ms ago)
I/PowerManagerService(  995): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  995): ALS enabled for SRE
D/PowerManagerServiceEx(  995): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36090 ms ago)
W/ContextImpl(  995): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  995): Sleeping (uid 1000)...
D/LPWGController(  995): [updateScreenState] screen on = false
D/LPWGController(  995): disable proximity sensor
D/LPWGController(  995): enable proximity sensor
I/SensorManager(  995): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1c6fefec] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  995): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  995): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  995): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  995): activate: handle is 48, enable
V/sensors_hal_Ctx(  995): activate sensors is 1400000000000
D/sensors_hal_Thresh(  995): enable: handle=48
I/sensors_hal_SAM(  995): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  995): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  995): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  995): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  995): enable: Received response: 0
D/PowerManagerServiceEx(  995): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36129 ms ago)
I/Adreno-EGL(  995): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  995): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  995): Build Date: 03/02/15 Mon
I/Adreno-EGL(  995): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  995): Remote Branch: 
I/Adreno-EGL(  995): Local Patches: 
I/Adreno-EGL(  995): Reconstruct Branch: 
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (983 us)
,I/Sensors (  418): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  995): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  995): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  995): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  995): processInd: handle 48, count=1
V/sensors_hal_Thresh(  995): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  995): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  995): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  995): poll: count: 256
I/sensors_hal_Ctx(  995): poll: released wakelock sensor_ind
D/sensors_hal_Util(  995): waitForResponse: timeout=0
D/LPWGController(  995): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  995): current mode = 1  value = 1 1
I/LPWGController(  995): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  995): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  995): set_light_backlight: 0
,I/SensorManager(  995): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  995): activate: handle is 46, disable
V/sensors_hal_Ctx(  995): activate sensors is 1000000000000
D/sensors_hal_LP2(  995): enable: handle=46
D/sensors_hal_LP2(  995): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  995): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
I/DisplayManagerService(  995): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  995): Display changed displayId=0
V/sensors_hal_SAM(  995): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  995): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1753): Display #0 changed.
,D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  995): Excessive delay in setPowerMode(): 215ms
I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  995): Got set_interactive hint
,D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1334): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1374): notifyScreenOffLocked
D/SmartCoverViewMediator( 1334): notifyScreenOffLocked
D/SmartCoverViewMediator( 1334): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1374): handleNotifyScreenOff
D/WifiServerServiceExt(  995): sendKtScanInterval  mRtspPlay : false
,D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 995
,D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: enter: screen_state=on
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  278): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
I/WifiServerServiceExt(  995): set CMD_KT_SCAN_INTERVAL
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
,D/GpsLocationProvider(  995): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1841): |CORE| sendScreenState: state:true
I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1804): stopPatternFlashing()
D/Cliptray Service( 1804): lockStatus = 0
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1787): action : android.intent.action.SCREEN_ON
I/LEDService( 1804): updateLightsLocked : turn off led
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1804): RESTART MSG
,D/NfcServiceNXP( 1787): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1787): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1787): isRequireNfcCRouting() return true
D/LNfcService( 1787): isHCERoutingtoHost() return : true
D/NfcService( 1787): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): newParams.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): screenState= 3
D/NfcService( 1787): Discovery configuration equal, not updating.
D/SplitWindow(  995): check instance of lgWin Window{1c9619bb u0 SearchPanel}
,D/InputDispatcher(  995): Window went away: Window{c915472 u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,D/Ulp_jni (  995): JNI:system_update. Event-0
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,I/Sensors (  418): sns_pwr.c(301):releasing wakelock
D/WeatherService( 2682): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:13:31
,D/WeatherService( 2682): 2 : ACTION screen on
D/WeatherService( 2682): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2682): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2682): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:13:31
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): ACTION_SCREEN_ON
D/AppCleanupService( 4081): android.intent.action.SCREEN_ON
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 995
,D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
D/WifiController(  995): CMD_SCREEN_OFF 
D/WifiController(  995): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  995): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1841): |CORE| sendScreenState: state:false
,I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1804): clear
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1787): action : android.intent.action.SCREEN_OFF
I/LEDService( 1804): updateLightsLocked : turn on led
E/LEDService( 1804): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1804): Can't handle this request of patternId:0
D/LEDHandler( 1804): RESTART MSG
D/NfcServiceNXP( 1787): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1879): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2682): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:13:31
D/WeatherService( 2682): 2 : ACTION screen off
D/WeatherService( 2682): 2 : TimeTick Receiver Unregister
D/WeatherService( 2682): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:13:31
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): ACTION_SCREEN_OFF
D/AppCleanupService( 4081): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4081): AppUsageStatsSaveTask
E/NxpNfcJni( 1787): getReconnectState = 0x0
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1787): getDefaultRoute
D/LNfcService( 1787): isRequireNfcCRouting() return true
D/LNfcService( 1787): isHCERoutingtoHost() return : true
D/NfcService( 1787): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): newParams.techmask= mTechMask: 0
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): screenState= 1
E/NxpNfcJni( 1787): getReconnectState = 0x0
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{9621ed8 type 2 when 161997 com.android.systemui} when 161997
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
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 175304598947; DSPS: 5843061; Offset : -3022730486
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1991): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  995): battery changed pluggedType: 2
I/ClearcutLoggerApiImpl( 1734): disconnect managed GoogleApiClient
,D/PowerManagerServiceEx(  995): acquireWakeLockInternal: lock=1051057766, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=995
,V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{173d2231 type 2 when 188018 com.google.android.gms} when 188018
D/PowerManagerServiceEx(  995): releaseWakeLockInternal: lock=1051057766 [*alarm*], flags=0x0
,I/PhenotypeConfigurator( 1734): Scheduling Phenotype for one-off execution 9704 seconds from now (1449681241788)
,D/GetConfigurationSnapshotOperation( 1734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  995): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 1734): propertyValue:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{355048ee type 2 when 189039 android} when 189039
,D/LocationManagerService(  995): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
,D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  995): android: cancelAsUser(2) by android
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
D/LocationManagerService(  995): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  995): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  995): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  995): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  995): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 195305312793; DSPS: 6498444; Offset : -3022720237
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 215306077526; DSPS: 7153829; Offset : -3022716751
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 235306757414; DSPS: 7809211; Offset : -3022708225
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/HeadsetStateMachine( 1991): Disconnected process message: 10, size: 0
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  995): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 255307521573; DSPS: 8464596; Offset : -3022707187
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 275308202242; DSPS: 9119979; Offset : -3022728239
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1991): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 295308986453; DSPS: 9775364; Offset : -3022707151
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1991): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  995): battery changed pluggedType: 2
D/HeadsetStateMachine( 1991): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/HeadsetStateMachine( 1991): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  995): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 315309824206; DSPS: 10430752; Offset : -3022723733
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1991): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  995): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 335310725241; DSPS: 11086141; Offset : -3022707787
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  995): remove 3e6d4825
D/LocationManagerService(  995): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  995): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  995): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  995): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  995): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  995): acquireWakeLockInternal: lock=1051057766, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=995
,V/AlarmManager(  995): RTC_WAKEUP set : Alarm{37487c6 type 0 when 1449681322807 com.google.android.gms} when 1449681322807
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ActivityManager(  995): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7671 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/EventLogService( 4245): Aggregate from 1449681166530 (log), 1449679522722 (data)
,I/DigitalAppWidgetProvider( 7671): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7671): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@348070ba
I/ActivityManager(  995): Killing 7397:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_10023/pid_7397/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx(  995): releaseWakeLockInternal: lock=1051057766 [*alarm*], flags=0x0
D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 355311456431; DSPS: 11741525; Offset : -3022708862
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1991): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  995): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 375312219601; DSPS: 12396910; Offset : -3022708891
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 395312975739; DSPS: 13052295; Offset : -3022715460
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 415313737867; DSPS: 13707680; Offset : -3022716296
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1991): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  995): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 435314411557; DSPS: 14363062; Offset : -3022714384
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 455315087955; DSPS: 15018444; Offset : -3022708878
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6055): Toggling radios to false
I/jxcore-log( 6055): 
,D/BluetoothManagerService(  995): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  995): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@c24a123 mBinding = false
D/BluetoothManagerService(  995): Message: 2
,D/BluetoothAdapterService(657717108)( 1991): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d367c6a
D/BluetoothManagerService(  995): Sending off request.
D/LocationManagerService(  995): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  995): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  995): JNI:system_update. Event-4
D/BluetoothAdapterService(657717108)( 1991): disable() called...
D/WifiServiceImplEx(  995): setWifiEnabled: false pid=6055, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  995): setWifiEnabled: false pid=6055, uid=10316
,D/BluetoothAdapterService(657717108)( 1991): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d367c6a
D/BluetoothAdapterService(657717108)( 1991): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d367c6a
D/BluetoothAdapterState( 1991): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1991): Setting state to 13
I/BluetoothAdapterState( 1991): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService(657717108)( 1991): updateAdapterState() - Broadcasting state to 1 receivers.
I/jxcore-log( 6055): Radios toggled
I/jxcore-log( 6055): 
E/WifiStateMachine(  995): WifiStateMachine: Leaving Connected state
,D/LocationManagerService(  995): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  995): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  995): JNI:system_update. Event-4
E/WifiConfigStore(  995): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothAdapterProperties( 1991): onBluetoothDisable()
,D/LGWifiP2pService(  995): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  995): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothAdapterService(657717108)( 1991): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d367c6a
D/CommandListener(  274): Clearing all IP addresses on wlan0
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
I/BluetoothAdapterState( 1991): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/DhcpStateMachine(  995): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  995): Message: 60
I/bt-btif ( 1991): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothAdapterProperties( 1991): Scan Mode:20
D/BluetoothAdapterState( 1991): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 1991): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 1991): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/BluetoothManagerService(  995): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  995): Bluetooth State Change Intent: 12 -> 13
D/bt-btif ( 1991): btsock_ctrl_hci_cleanup(L202): poll handle:4
I/bt-btif ( 1991): BTA_JvDeleteRecord
V/NativeCrypto( 1734): Read error: ssl=0xb045a400: I/O error during system call, Connection timed out
,I/bt-btif ( 1991): BTA_JvRfcommStopServer
I/bt-btif ( 1991): BTA_JvDeleteRecord
I/bt-btif ( 1991): BTA_JvRfcommStopServer
W/bt-btif ( 1991): invalid rfc slot id: 1
D/IOP_DB_BT( 1991): db_close: nbr users 0
D/IOP_DB_BT( 1991): db_close: free database
D/btif_config_util( 1991): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 1991): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 1991): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 1991): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 1991): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 1991): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:G3s-1
D/btif_config_util( 1991): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 1991): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 1991): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 1991): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 1991): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 1991): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 1991): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 1991): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 1991): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 1991): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 1991): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 1991): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 1991): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 1991): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 1991): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 1991): enum_config(L344): out, value:x
D/btif_config_util( 1991): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 1991): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 1991): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 1991): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 1991): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 1991): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
,D/btif_config_util( 1991): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 1991): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 1991): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 1991): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 1991): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 1991): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 1991): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 1991): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 1991): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 1991): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 1991): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 1991): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:�
D/btif_config_util( 1991): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 1991): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:,b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 1991): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
,D/btif_config_util( 1991): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:$
D/btif_config_util( 1991): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 1991): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
,D/btif_config_util( 1991): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
,D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
,D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 ,
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:�
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:A5-1
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1991): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:cf:c5:d9:e5,:61, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:#
D/btif_config_util( 1991): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 1991): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1991): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:�
D/btif_config_util( 1991): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:XT1072
D/btif_config_util( 1991): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 10
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
D/btif_config_util( 1991): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:a
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:S5-1
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1991): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:	a
D/btif_config_util( 1991): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:G4-1
D/btif_config_util( 1991): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1991): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:a
D/btif_config_util( 1991): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:Thali Test (Galaxy S5)
D/btif_config_util( 1991): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 000,0112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:�
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:Thali Test (Galaxy A5)
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:�
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:A
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:Thali Test's G2
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:	a
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:Note3-1
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:�
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:A3-1
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1991): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:�
D/btif_config_util( 1991): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:XT1039
D/btif_config_util( 1991): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:	a
I/BluetoothMapService( 1991): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/BluetoothMapService( 1991): STATE_TURNING_OFF
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1991): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:�
D/btif_config_util( 1991): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string,
D/btif_config_util( 1991): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:HTC One_M8
D/btif_config_util( 1991): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1991): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:"
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:Note4-1
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1991): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:�
D/btif_config_util( 1991): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 1991): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 1991): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 1991): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 1991): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 1991): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 1991): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 1991): enum_config(L343): out, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 1991): enum_config(L300): in, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 1991): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1991): enum_config(L343): out, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 1991): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 1991): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:���
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 1991): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 1991): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:ALE-L21
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 1991): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 1991): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 1991): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 1991): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1991): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 1991): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:#
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L344): out, value:onem9-1
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 1991): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:H
D/btif_config_util( 1991): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 1991): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:?C
D/btif_config_util( 1991): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 1991): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 1991): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 1991): enum_config(L300): in, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 1991): enum_config(L343): out, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Service, value type:string
D/btif_config_util( 1991): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 1991): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 1991): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 1991): enum_config(L300): in, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 1991): enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:08:00:00:00:67:73, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:00:00:00:67:73, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:�
D/btif_config_util( 1991): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:Galaxy S5-2
D/btif_config_util( 1991): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpVer, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpSubVer, value type:int
D/btif_config_util( 1991): enum_confi,g(L343): out, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 1991): enum_config(L344): out, value:�
D/btif_config_util( 1991): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:A3-1
D/btif_config_util( 1991): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:Z
D/btif_config_util( 1991): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:JustWorks, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:GlobalTrust, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:Name, value type:string
D/btif_config_util( 1991): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 1991): enum_config(L344): out, value:$��
D/btif_config_util( 1991): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:`��
D/btif_config_util( 1991): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
D/btif_config_util( 1991): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevClass, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 1991): enum_config(L344): out, value:���
D/btif_config_util( 1991): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 1991): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevType, value type:int
D/btif_config_util( 1991): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 1991): enum_config(L344): out, value:
I/[SystemUI]BluetoothHandler( 1374): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  995): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  995): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
W/bt-btif ( 1991): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/NativeCrypto( 1734): SSL shutdown failed: ssl=0xb045a400: I/O error during system call, Broken pipe
E/bt-btif ( 1991): btif_hf_upstreams_evt: wrong handle = 1280 
W/bt-obex ( 1991): Ignore event 10 in state 1
W/bt-obex ( 1991): Ignore event 10 in state 1
I/bt-btif ( 1991): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1991): ops_state_cb(L223):  ops_state_cb state:3
V/BluetoothPbapService( 1991): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/OppService( 1991): onOpsStateChange() :3
E/bt-btif ( 1991): bta_gattc_deregister Deregister Failedm unknown client cif
V/BluetoothMapMasInstance( 1991): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 1991): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 1991): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 1991): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 1991): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 1991): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 1991): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 1991): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/LGBluetoothMapAdapter( 1991): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1991): MAP Service closeService out
D/OppService( 1991): Recieved MESSAGE_OPS_DISABLE
D/ConnectivityService(  995): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  995): disableDataServiceNotify
D/DSQN    (  995): stop dsqn bin
D/ConnectivityService(  995): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10006
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): ValidatedState{ when=-1ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): DefaultState{ when=-1ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): Forcing reevaluation
D/ConnectivityService(  995): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  995):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  995):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/ActivityManager(  995): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7767 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/WifiHS20(  995): hidePasspointNotification off =false
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  995): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/Nat464Xlat(  995): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/WifiHS20(  995): hidePasspointNotification off =false
,D/CSLegacyTypeTracker(  995): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  995): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  995): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNetworkAgent(  995): NetworkAgent: NetworkAgent channel lost
D/LGWifiP2pService(  995): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  995): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  995): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  995): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiScanningService(  995): SCAN_AVAILABLE : 1
V/NetworkPolicy(  995): [LG_RESTRICTED] !!!isConnected  type  :1
D/RttService(  995): SCAN_AVAILABLE : 1
D/WifiScanningService(  995): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  995): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  995): MasterInitialState.processMessage what=3
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 457us total 33.276ms
,I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:18:39.104 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:18:39.105 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524292
D/ConnectivityService(  995): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  995): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  995): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  995): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  995):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/LGWifiP2pService(  995): P2pDisablingState
D/LGWifiP2pService(  995): P2pDisablingState{ when=-17ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  995): p2p socket connection lost
D/LGWifiP2pService(  995): P2pDisabledState
D/NetworkManagementService(  995): Removing idletimer
W/Settings(  995): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  995): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
W/QCNEJ   ( 1841): |CORE| No family connected
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
D/Tethering(  995): MasterInitialState.processMessage what=3
V/NetworkPolicy(  995): [LG_RESTRICTED] !!!isConnected  type  :1
D/LGWifiP2pService(  995): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  995): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): ValidatedState{ when=-37ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): DefaultState{ when=-37ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  995): Disconnected - quitting
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.n,et.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,W/QCNEJ   ( 1841): |CORE| No family connected
I/QCNEJ   ( 1841): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/WfdsService( 1804): WifiP2pState is changed : false
D/WfdsService( 1804): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsJNI ( 1804): doCommand: P2P_STOP_FIND
I/QCNEJ   ( 1841): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1753): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CommandListener(  274): Clearing all IP addresses on wlan0
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WfdsService( 1804): Set the WFDS Monitor: false
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 422us total 31.844ms
D/DhcpStateMachine(  995): StoppedState
D/DhcpStateMachine(  995): StoppedState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1804): WFDS Monitor is stopped
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
D/CtrlSupplicant( 1804): Received on exit socket, terminate
E/CtrlSupplicant( 1804): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/WfdsService( 1804): STATE : WfdsDisabledState - enter
D/WfdsService( 1804): WFDS: Scanner is paused
,D/WfdsMonitor( 1804): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1804): WfdsMonitorThread is received the interrupt - closing
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:18:39.136 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WfdsDiscoveryStore( 1804): Clear Discovery Method Map: ScanAlwaysMode false
W/WfdsSession:Controller( 1804): DefaultState - msg [9441355] is not handled
D/WifiHS20(  995): hidePasspointNotification off =false
W/Settings(  995): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  995): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  995): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:18:39.148 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/WifiServerServiceExt(  995): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt(  995): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  995): setSupplicantStateDISCONNECTED
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 444us total 31.096ms
,D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 5
,I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 10
I/wpa_supplicant( 2815): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2815): monitor socket send errors count : 1
I/wpa_supplicant( 2815): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1804-2\x00 that cannot receive messages
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 7
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/wpa_supplicant( 2815): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,W/wpa_supplicant( 2815): USIM:  scard_deinit function
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.p2p.STATE_CHANGED at null
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd(  995): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  995): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.WIFI_STATE_CHANGED at null
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 5
I/wpa_supplicant( 2815): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  995): InitialState.processMessage what=4
D/Tethering(  995): sendTetherStateChangedBroadcast 0, 0, 0
,W/ResourcesManager( 7767): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7767): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7767): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7767): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7767): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/WfdsService( 1804): Supplicant Connection state is changed : false
D/WfdsService( 1804): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1804): Set the WFDS Monitor: false
,D/WfdsMonitor( 1804): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed(  995): stopMonitoring
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 18:18:39.444 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  995): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt(  995): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt(  995): batteryPsActivateMsgHandler : this is not treated
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.WIFI_STATE_CHANGED at null
W/Settings( 1734): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/IndexDatabaseHelper( 7767): Using schema version: 115
,I/IndexDatabaseHelper( 7767): Index is fine
I/ActivityManager(  995): Process com.google.android.apps.plus (pid 7254) has died
,W/ContextImpl( 7767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 1991): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1991): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1991): ***********state = 13
V/BluetoothPbapReceiver( 1991): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 1991): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapService( 1991): state: 13
,V/BluetoothPbapService( 1991): Pbap Service closeService in
V/BluetoothPbapService( 1991): successfully stopped pbap service
V/BluetoothPbapService( 1991): Pbap Service closeService out
V/BluetoothPbapService( 1991): Pbap Service onDestroy
V/BluetoothPbapService( 1991): Pbap Service closeService in
V/BluetoothPbapService( 1991): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 1991): [BTUI] cleanup
V/WiFiOffLoadBroadcast( 7767): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7767): MCCMNC not supported: null
,D/BluetoothManagerService(  995): Message: 20
D/BluetoothManagerService(  995): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1156c99e:true
,D/BluetoothAdapterService(657717108)( 1991): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d367c6a
,D/BluetoothManagerService(  995): Message: 30
D/BluetoothManagerService(  995): Message: 30
I/ActivityManager(  995): Process com.android.contacts (pid 7421) has died
,D/LocalBluetoothProfileManager( 7767): Adding local MAP profile
D/BluetoothMap( 7767): Create BluetoothMap proxy object
D/BluetoothManagerService(  995): Message: 30
D/BluetoothManagerService(  995): Message: 30
D/LocalBluetoothProfileManager( 7767): LocalBluetoothProfileManager construction complete
,D/LGBluetoothFeatureConfig( 7767):  get() - isFeatureLoaded : false
D/LGBluetoothUserBindClient( 7767): [BTUI] initUserBindClient
,W/ContextImpl( 7767): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 7767): finishStartingService: stopping service
,D/BluetoothInputDevice( 7767): Proxy object connected
,D/HidProfile( 7767): Bluetooth service connected
D/BluetoothAdapterService(657717108)( 1991): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d367c6a
D/BluetoothPan( 7767): BluetoothPAN Proxy object connected
D/PanProfile( 7767): Bluetooth service connected
D/BluetoothAdapterService(657717108)( 1991): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d367c6a
D/BluetoothMap( 7767): Proxy object connected
D/MapProfile( 7767): Bluetooth service connected
D/BluetoothMap( 7767): getConnectedDevices()
D/BluetoothAdapterService(657717108)( 1991): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d367c6a
D/BluetoothMap( 7767): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7767): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 7767): [BTUI] cancel All Notification
,I/NotificationManager( 7767): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 7767): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 7767): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 7767): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 7767): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 7767): com.android.settings: cancel(-1000041) by com.android.settings
I/ActivityManager(  995): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7797 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BluetoothPermissionRequest( 7767): onReceive
,D/LGBluetoothAuthorization( 7767): [BTUI] cancel All Notification
I/NotificationManager( 7767): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 7767): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 7767): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 7767): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 7767): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 7767): com.android.settings: cancel(-1000041) by com.android.settings
V/BluetoothOppReceiver( 1991): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 1991): [BTUI] cancel opp incoming file confirm notification
I/NotificationManager( 1991): com.android.bluetooth: cancel(-1) by com.android.bluetooth
,D/BluetoothOppNotification( 1991): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 1991): com.android.bluetooth: cancel(-1) by com.android.bluetooth
V/BluetoothSapReceiver( 1991): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 1991): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
I/ActivityManager(  995): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7815 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/bt_userial( 1991): select_read return size <=0:0, exiting userial_read_thread
D/bt_hwcfg( 1991): hw_epilog_process
I/bt_userial_vendor( 1991): device fd = 68 close
,W/bt-l2cap( 1991): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1991): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1991): ag scb idx 1 not allocated
E/bt-btif ( 1991): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1991): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1991): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1991): ag scb idx 1 not allocated
E/bt-btif ( 1991): BTA AG is already disabled, ignoring ...
E/bt-btif ( 1991): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 1991): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt_vendor( 1991): [BTUI] Proto is enabled. Set Proto disable!!
,W/ResourcesManager( 7815): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/PCSuite ( 7797): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7797): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7797): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/AuthorizationBluetoothService( 1734): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/WiFiOffLoadBroadcast( 7767): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7767): MCCMNC not supported: null
I/GKI_LINUX( 1991): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,I/GKI_LINUX( 1991): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1991): GKI_destroy_task(): task [BTU] terminated
I/bt-btif ( 1991): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 1991): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1991): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
I/PCSuite ( 7797): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7797): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7797): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BtSettings.ProfileConfig( 1991): Unable to read settings
D/BtSettings.ProfileConfig( 1991): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1991): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1991): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1991): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1991): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1991): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 1991): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 1991): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1991): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1991): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1991): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1991): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1991): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(657717108)( 1991): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
,D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1991): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
,D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1991): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(657717108)( 1991): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1991): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/HeadsetService( 1991): Received stop request...Stopping profile...
W/BluetoothAdapterService( 1991): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(657717108)( 1991): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
I/ActivityManager(  995): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7843 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
,W/BluetoothAdapterService( 1991): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1991): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(657717108)( 1991): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
I/ActivityManager(  995): Killing 7440:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/LGBluetoothHfpAdapter( 1991): [BTUI] LGBluetoothHfpAdapter cleanup
D/HeadsetStateMachine( 1991): Exit Disconnected: -1
W/LGBluetoothHeadsetServiceJni( 1991): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1991): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2733f774
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1991): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1991): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(657717108)( 1991): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
W/libprocessgroup(  995): failed to open /acct/uid_10069/pid_7440/cgroup.procs: No such file or directory
,D/BluetoothHeadset( 1753): Proxy object disconnected
D/BluetoothHeadset(  995): Proxy object disconnected
D/A2dpService( 1991): Received stop request...Stopping profile...
D/A2dpStateMachine( 1991): Exit Disconnected: -1
D/AudioService(  995): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1991): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1991): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(657717108)( 1991): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1991): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1991): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(657717108)( 1991): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
,D/BluetoothHeadset( 1753): Proxy object disconnected
D/BluetoothHeadset( 1753): Proxy object disconnected
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1991): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1991): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(657717108)( 1991): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1991): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1991): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(657717108)( 1991): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1991): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1991): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1991): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(657717108)( 1991): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
D/LGBluetoothA2dpAdapter( 1991): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 1991): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 1991): [BTUI] terminate
D/BluetoothManagerService(  995): Message: 31
D/BluetoothAdapterService( 1991): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2733f774
D/BluetoothA2dp(  995): Proxy object disconnected
D/AudioService(  995): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 1991): Received stop request...Stopping profile...
D/BluetoothAdapterState( 1991): Stopping profile services that were post enabled
D/BluetoothAdapterService( 1991): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2733f774
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - Message: 1
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothInputDevice( 7767): Proxy object disconnected
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 1991): isTurningOnRadio()=false
D/BluetoothAdapterState( 1991): isTurningOffRadio()=false
D/HidProfile( 7767): Bluetooth service disconnected
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1991): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1991): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,D/HealthService( 1991): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1991): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2733f774
D/HeadsetStateMachine( 1991): Unbinding service...
D/HeadsetPhoneState( 1991): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1991): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 1991): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1991): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 1991): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1991): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 1991): [BTUI] LGBluetoothHfpAdapter cleanup
D/PanService( 1991): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1991): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2733f774
D/BluetoothPan( 7767): BluetoothPAN Proxy object disconnected
D/PanProfile( 7767): Bluetooth service disconnected
D/BtGatt.DebugUtils( 1991): handleDebugAction() action=null
D/BtGatt.GattService( 1991): Received stop request...Stopping profile...
D/BtGatt.GattService( 1991): stop()
D/BtGatt.AdvertiseManager( 1991): advertise clients cleared
D/LGBluetoothGattAdapter( 1991): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 1991): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2733f774
D/BluetoothMapService( 1991): Received stop request...Stopping profile...
D/BluetoothMapService( 1991): stop()
D/BluetoothMapEmailAppObserver( 1991): deinitObservers()
D/BluetoothMapEmailAppObserver( 1991): removeReceiver()
D/BluetoothAdapterService( 1991): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2733f774
W/ResourcesManager( 7843): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/SapService( 1991): Received stop request...Stopping profile...
D/SapService( 1991): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 1991): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 1991): [BTUI] terminateSapManager
D/BluetoothMap( 7767): Proxy object disconnected
D/MapProfile( 7767): Bluetooth service disconnected
,D/BluetoothAdapterService( 1991): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2733f774
D/**BluetoothFTPService( 1991): Received stop request...Stopping profile...
D/**BluetoothFTPService( 1991): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 1991): closeFtpServerNative
D/BluetoothAdapterService( 1991): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2733f774
D/LgeBluetoothSimManager( 1753): [BTUI] SAP_DISABLE_EVT
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - Message: 1
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 1991): isTurningOnRadio()=false
D/BluetoothAdapterState( 1991): isTurningOffRadio()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1991): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1991): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/**OppService( 1991): Received stop request...Stopping profile...
D/OppService( 1991): Stopping Bluetooth OppService
D/OppService( 1991): cleanup OPP Service
W/BluetoothOPPServiceJni( 1991): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 1991): Cleaning up Bluetooth OPP callback object
D/OppService( 1991): remove callbacks and handler
D/LGBluetoothOppAdapter( 1991): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 1991): cleanup done
D/BluetoothAdapterService( 1991): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2733f774
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - Message: 1
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 1991): isTurningOnRadio()=false
D/BluetoothAdapterState( 1991): isTurningOffRadio()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1991): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1991): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/BluetoothA2dpServiceJni( 1991): cleanupNative
I/GKI_LINUX( 1991): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1991): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1991): GKI_destroy_task(): task [A2DP-MEDIA] terminated
,W/BluetoothHidServiceJni( 1991): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 1991): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - Message: 1
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 1991): isTurningOnRadio()=false
D/BluetoothAdapterState( 1991): isTurningOffRadio()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1991): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1991): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 1991): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1991): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 1991): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - Message: 1
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 1991): isTurningOnRadio()=false
D/BluetoothAdapterState( 1991): isTurningOffRadio()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1991): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1991): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 1991): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1991): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - Message: 1
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 1991): isTurningOnRadio()=false
D/BluetoothAdapterState( 1991): isTurningOffRadio()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1991): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1991): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1991): Handler(): got msg=4
D/BluetoothMapService( 1991): MAP Service closeService in
D/LGBluetoothMapAdapter( 1991): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1991): MAP Service closeService out
D/,BluetoothAdapterService(657717108)( 1991): handleMessage() - Message: 1
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 1991): isTurningOnRadio()=false
D/BluetoothAdapterState( 1991): isTurningOffRadio()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1991): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1991): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 1991): cleanup()
D/BluetoothMapService( 1991): MAP Service closeService in
D/LGBluetoothMapAdapter( 1991): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1991): MAP Service closeService out
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - Message: 1
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 1991): isTurningOnRadio()=false
D/BluetoothAdapterState( 1991): isTurningOffRadio()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1991): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1991): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 1991): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 1991): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - Message: 1
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 1991): isTurningOnRadio()=false
D/BluetoothAdapterState( 1991): isTurningOffRadio()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1991): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1991): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1991): Profile still running: com.broadcom.bt.service.opp.OppService
,D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothFTPService( 1991): cleanup FTP Service
V/BluetoothFTPServiceJni( 1991): closeFtpServerNative
V/BluetoothFTPServiceJni( 1991): cleanupNative
W/BluetoothFTPServiceJni( 1991): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 1991): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 1991): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 1991): cleanup done
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - Message: 1
D/BluetoothAdapterService(657717108)( 1991): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
,D/BluetoothAdapterState( 1991): isTurningOnRadio()=false
D/BluetoothAdapterState( 1991): isTurningOffRadio()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1991): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1991): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(657717108)( 1991): onProfileServiceStateChange() - All profile services stopped...
D/OppService( 1991): cleanup OPP Service
D/OppService( 1991): remove callbacks and handler
D/LGBluetoothOppAdapter( 1991): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 1991): cleanup done
D/BluetoothAdapterState( 1991): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1991): Setting state to 10
I/BluetoothAdapterState( 1991): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(657717108)( 1991): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  995): Message: 60
D/BluetoothManagerService(  995): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  995): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 1991): Entering OffState
D/BluetoothHeadset( 1753): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1753): onBluetoothStateChange: up=false
D/BluetoothPbap( 7767): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7767): onBluetoothStateChange: up=false
D/BluetoothMap( 7767): onBluetoothStateChange: up=false
D/BluetoothPan( 7767): onBluetoothStateChange on: false
D/BluetoothHeadset( 1753): onBluetoothStateChange: up=false
D/BluetoothA2dp(  995): onBluetoothStateChange: up=false
D/BluetoothHeadset(  995): onBluetoothStateChange: up=false
D/BluetoothAdapterService(657717108)( 1991): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d367c6a
D/BluetoothManagerService(  995): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  995): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothManagerService(  995): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  995): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService(  995): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@c24a123 mBinding = false
,D/BluetoothManagerService(  995): Sending unbind request.
D/BluetoothAdapterService(657717108)( 1991): onUnbind() - calling cleanup
D/BluetoothAdapterService(657717108)( 1991): cleanup()
D/BluetoothManagerService(  995): Bluetooth State Change Intent: 13 -> 10
D/LGBluetoothAPIService( 1804): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1804): Message: 2
D/LGBluetoothFeatureConfig( 7767): isPrivacyLogsEnabled : true
D/BluetoothAdapter( 1374): 372870184: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1374): 372870184: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothAPIService( 1804): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@33bd98b3 mBinding = false
D/LGBluetoothAPIService( 1804): Sending unbind request.
,D/BluetoothAdapterService(657717108)( 1991): cleanup() - Cleaning up adapter native
I/bt-btif ( 1991): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 1991): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/bt-btif ( 1991): HAL bt_hal_cbacks->thread_evt_cb
D/LGBluetoothUtils( 7767): [BTUI] resetProperty - success
E/LGBluetoothEventManager( 7767): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7767): [BTUI] clear device connection state
I/GKI_LINUX( 1991): gki_task task_id=1 [BTIF] terminating
I/[SystemUI]BluetoothHandler( 1374): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
I/GKI_LINUX( 1991): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 1991): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1991): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1991): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1991): GKI_exit_task 2 done
I/GKI_LINUX( 1991): GKI_exit_task 1 done
I/GKI_LINUX( 1991): GKI_exit_task 0 done
I/BluetoothServiceJni( 1991): cleanupNative: return from cleanup
W/LGBluetoothServiceJni( 1991): Cleaning up Bluetooth Service callback object
W/ContextImpl( 7767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LGBluetoothSettingsDBObserver( 1991): [BTUI] unregister observer for LG device name DB
D/BluetoothAdapterService(657717108)( 1991): cleanup() - Bluetooth process exited normally.
D/BluetoothAdapterService(657717108)( 1991): cleanup() done
I/art     ( 1991): System.exit called, status: 0
I/AndroidRuntime( 1991): VM exiting with result code 0, cleanup skipped.
D/DockEventReceiver( 7767): finishStartingService: stopping service
,V/AudioFlinger(  278): 1991 died, releasing its sessions
V/AudioFlinger(  278):  pid 1753 @ 0
V/AudioFlinger(  278):  pid 3175 @ 1
V/AudioFlinger(  278):  pid 3175 @ 2
,D/LGBluetoothUserBindClient( 7767): [BTUI] onServiceDisconnected
D/FMFRW_FmProxy( 1804): Fm Proxy object disconnected
D/BluetoothAdapter( 1734): 770189961: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1734): 770189961: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  995): Process com.android.bluetooth (pid 1991) has died
,W/ActivityManager(  995): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 1000ms
,W/ActivityManager(  995): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
I/art     (  995): Explicit concurrent mark sweep GC freed 81860(4MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.500ms total 180.620ms
,D/BluetoothPermissionRequest( 7767): onReceive
,D/LGBluetoothUtils( 7767): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7767): cancelDiscoverableAlarm(): Enter
I/ActivityManager(  995): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7869 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
,W/ResourcesManager( 7869): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 7869): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7869): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 7869): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 7869): Loading JNI Library
,I/Babel_SMS( 7843): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7843): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7843): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7843): MmsConfig.loadFromDatabase
E/BluetoothServiceJni( 7869): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
,D/BluetoothAdapterApp( 7869): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1a77f94f Instance Count = 1
D/BluetoothAdapterApp( 7869): onCreate
E/Babel_SMS( 7843): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7843): MmsConfig.loadFromResources
E/Babel_SMS( 7843): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7843): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/LGBluetoothServiceJni( 7869): classInitNative: succeeds
D/SensorManager( 7843): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 7843): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7843): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7843): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7843): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7843): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7843): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7843): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7843): found sensor: LGE Step Counter Sensor, handle=44
D/BtSettings.ProfileConfig( 7869): [BTUI] HeadsetServiceis supported
D/SensorManager( 7843): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7843): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7843): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7843): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7843): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7843): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7843): found sensor: Motion Accel, handle=46
D/BtSettings.ProfileConfig( 7869): Adding HeadsetService
,D/BtSettings.ProfileConfig( 7869): [BTUI] A2dpServiceis supported
D/BtSettings.ProfileConfig( 7869): Adding A2dpService
D/BtSettings.ProfileConfig( 7869): [BTUI] HidServiceis supported
D/BtSettings.ProfileConfig( 7869): Adding HidService
D/BtSettings.ProfileConfig( 7869): [BTUI] HealthServiceis supported
D/BtSettings.ProfileConfig( 7869): Adding HealthService
D/LGBluetoothFeatureConfig( 7869): isSupportPan() :  mTargetOp=OPEN
D/LGBluetoothFeatureConfig( 7869): isSupportPan() :  mTargetOp=OPEN
D/BtSettings.ProfileConfig( 7869): [BTUI] PanServiceis supported
D/BtSettings.ProfileConfig( 7869): Adding PanService
D/BtSettings.ProfileConfig( 7869): [BTUI] GattServiceis supported
D/BtSettings.ProfileConfig( 7869): Adding GattService
,D/BtSettings.ProfileConfig( 7869): [BTUI] BluetoothMapServiceis supported
D/BtSettings.ProfileConfig( 7869): Adding BluetoothMapService
V/LGBluetoothServiceAdapter( 7869): [BTUI] region:EU country:EU
D/BtSettings.ProfileConfig( 7869): [BTUI] SapServiceis supported
D/BtSettings.ProfileConfig( 7869): Adding SapService
D/BtSettings.ProfileConfig( 7869): [BTUI] FTPServiceis supported
D/BtSettings.ProfileConfig( 7869): Adding FTPService
E/BtSettings.ProfileConfig( 7869): [BTUI] HeadsetClientServiceis NOT supported
D/BtSettings.ProfileConfig( 7869): [BTUI] OppServiceis supported
D/BtSettings.ProfileConfig( 7869): Adding OppService
D/BtSettings.ProfileConfig( 7869): deviceMode from shared preference   -1
D/BtSettings.ProfileConfig( 7869): checkAndAdjustDeviceModeConfiguration deviceMode1
D/BtSettings.ProfileConfig( 7869): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 7869): Unable to read settings
D/BtSettings.ProfileConfig( 7869): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 7869): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 7869): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 7869): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 7869): 	at com.broadcom.bt.service.ProfileConfig.checkAndAdjustDeviceModeConfiguration(ProfileConfig.java:400)
D/BtSettings.ProfileConfig( 7869): 	at com.broadcom.bt.service.ProfileConfig.init(ProfileConfig.java:550)
D/BtSettings.ProfileConfig( 7869): 	at com.lge.bluetooth.adapter.LGBluetoothProfileConfigAdapter.init(LGBluetoothProfileConfigAdapter.java:30)
D/BtSettings.ProfileConfig( 7869): 	at com.android.bluetooth.btservice.AdapterApp.onCreate(AdapterApp.java:67)
D/BtSettings.ProfileConfig( 7869): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
D/BtSettings.ProfileConfig( 7869): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
D/BtSettings.ProfileConfig( 7869): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
D/BtSettings.ProfileConfig( 7869): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
D/BtSettings.ProfileConfig( 7869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 7869): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 7869): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
D/BtSettings.ProfileConfig( 7869): 	at java.lang.reflect.Method.invoke(Native Method)
D/BtSettings.ProfileConfig( 7869): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BtSettings.ProfileConfig( 7869): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
D/BtSettings.ProfileConfig( 7869): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/BtSettings.ProfileConfig( 7869): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 7869): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 7869): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 7869): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 7869): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 7869): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 7869): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 7869): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 7869): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/Settings( 7843): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGBluetoothOppAdapter( 7869): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/Babel_Crash( 7843): startup - clean
I/FmServiceJni( 7869): classInitNative: succeeds
,D/FmService( 7869): FmReceiverServiceStub createdcom.broadcom.fm.fmreceiver.FmService$FmReceiverServiceStub@348070baservicecom.broadcom.fm.fmreceiver.FmService@26e4db6b
D/FmNativehandler( 7869): start
D/BluetoothRadioManager( 7869): [BTUI] getRadioManager()
D/BluetoothRadioManager( 7869): [BTUI] BluetoothRadioManager()
,D/BluetoothManagerService(  995): Message: 20
D/BluetoothManagerService(  995): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3859797b:true
I/Babel   ( 7843): deleted: false for 0
D/BluetoothRadioManager( 7869): doBind: com.broadcom.bt.service.radiomanager.IBluetoothRadioManager
,V/FmService( 7869): FM Service  onCreate
,D/FmService( 7869): Binding service...
D/FMFRW_FmProxy( 1804): Fm proxy onServiceConnected() name = ComponentInfo{com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService}, service = android.os.BinderProxy@19b2be70
D/LGBluetoothUserBindClient( 7767): [BTUI] onServiceConnected
I/art     ( 7843): CheckpointMarkThreadRoots callback created = 0xb042d920
,V/WiFiOffLoadBroadcast( 7767): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/BluetoothAdapterService( 7869): Set JNI Library before classInit
,D/WiFiOffLoadBroadcast( 7767): MCCMNC not supported: null
I/PCSuite ( 7797): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7797): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7797): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothAdapterService(507372701)( 7869): AdapterService() - REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothAdapterService(507372701)( 7869): onCreate()
D/BluetoothAdapterState( 7869): make
I/BluetoothAdapterState( 7869): Entering OffState
V/WiFiOffLoadBroadcast( 7767): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
I/bluedroid( 7869): init
,W/AudioCapabilities( 7843): Unsupported mime audio/x-lg-flac
D/WiFiOffLoadBroadcast( 7767): MCCMNC not supported: null
I/bte_conf( 7869): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 7869): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 7869): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 7869): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 7869): [BTUI] lge_load_bluetooth_address
D/bt-btif ( 7869):  [BTUI] Load_abtddress
D/BTIF_CORE( 7869): [BTUI] lge_wait_for_load_bluetooth_address : success!
D/bt-btif ( 7869): PERSIST_BDADDR_PROPERTY is  F8:95:C7:87:85:54
D/bt-btif ( 7869): Got prior random BDA F8:95:C7:87:85:54
I/bluedroid( 7869): get_profile_interface socket
I/GKI_LINUX( 7869): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 7869): get_profile_interface map_client
D/bt-btif ( 7869): btif task starting
D/bt-btif ( 7869): btif_associate_evt: notify ASSOCIATE_JVM
E/BluetoothServiceJni( 7869): Error getting mapclient interface
I/bt-btif ( 7869): HAL bt_hal_cbacks->thread_evt_cb
I/bt-btif ( 7869): btif_get_adapter_property 2
I/bt-btif ( 7869): btif_get_adapter_property 1
I/art     ( 7843): CheckpointMarkThreadRoots callback created = 0xb042d900
I/bt-btif ( 7869): execute storage request event : 3
D/bt-btif ( 7869): btif_storage_get_adapter_property property->type:2 
I/bt-btif ( 7869): HAL bt_hal_cbacks->adapter_properties_cb
W/AudioCapabilities( 7843): Unsupported mime audio/adpcm
D/BluetoothAdapterProperties( 7869): Address is:F8:95:C7:87:85:54
I/bt-btif ( 7869): execute storage request event : 3
D/bt-btif ( 7869): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 7869): in, bd addr:, prop type:1, len:512
I/bt-btif ( 7869): HAL bt_hal_cbacks->adapter_properties_cb
W/AudioCapabilities( 7843): Unsupported mime audio/g726
,W/AudioCapabilities( 7843): Unsupported mime audio/x-ms-wma
D/lge_bdaddr_loader( 7911): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 7911): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 7911): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 7911): [BTUI] bdaddr to set in property : F8:95:C7:87:85:54
W/AudioCapabilities( 7843): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7843): Unsupported mime video/mjpg
,E/lge_bdaddr_loader( 7911): [BTUI] bluetooth_load_bdaddress : OK => F8:95:C7:87:85:54
D/lge_bdaddr_loader( 7911): [BTUI] bdaddr_loader ::: END
W/VideoCapabilities( 7843): Unsupported mime video/theora
,W/AudioCapabilities( 7843): Unsupported mime audio/evrc
,W/AudioCapabilities( 7843): Unsupported mime audio/qcelp
I/ActivityManager(  995): Process com.google.android.gms.unstable (pid 6901) has died
D/BluetoothAdapterProperties( 7869): Name is: G3s-1
,W/VideoCapabilities( 7843): Unrecognized profile 2130706433 for video/avc
D/PCSuite ( 7797): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothAdapterService( 7869): getAdapterService() - Service not available
D/LGBluetoothServiceAdapter( 7869): [BTUI] check adapter is available - false.
D/LGBluetoothSettingsDBObserver( 7869): [BTUI] register observer for LG device name DB
D/BluetoothManagerService(  995): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  995): Stored Bluetooth name: G3s-1
D/BluetoothAdapterService(507372701)( 7869): onBind()
V/BluetoothSapReceiver( 7869): [BTUI] checkServiceStart
D/BluetoothRadioManager( 7869): onServiceConnected: connected to AdapterService com.android.bluetooth.btservice.AdapterService
D/BluetoothRadioManager( 7869): Message: 40
D/BluetoothRadioManager( 7869): MESSAGE_RADIO_SERVICE_CONNECTED: 1
D/BluetoothRadioManager( 7869):  Turning on BT modules Radio on = false
,D/UsbSettingsReceiver( 7767): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 7767): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7767): [AUTORUN] sys.usb.state = ptp_only,adb
D/LGBluetoothStateChangeReceiver( 7869): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/UsbSettingsReceiver( 7767): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7767): [AUTORUN] onReceive() : app userid = 0, current userid = 0
W/AudioCapabilities( 7843): Unsupported mime audio/amr-wb-plus
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7815): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
W/AudioCapabilities( 7843): Unsupported mime audio/qcelp
D/AuthorizationBluetoothService( 1734): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/AudioCapabilities( 7843): Unsupported mime audio/evrc
,D/UsbSettingsControl( 7767): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7767): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7767): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7767): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7767): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7767): [AUTORUN] setTetherStatus() : status=false
,W/VideoCapabilities( 7843): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7843): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7843): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7843): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7843): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7843): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  995): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7916 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/vclib   ( 7843): onServiceConnected
,W/Babel   ( 7843): Attempted to change video mute state without an active call.
I/NotificationManager( 7843): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/LGDMClient( 7916): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 7916): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7916): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7916): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/WiFiOffLoadBroadcast( 7767): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WiFiOffLoadBroadcast( 7767): MCCMNC not supported: null
,I/PCSuite ( 7797): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7797): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7797): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 7916): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 7916): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7916): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/ActivityManager(  995): Killing 7464:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10036/pid_7464/cgroup.procs: No such file or directory
,D/ConnectivityService(  995): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  995): onReceive
D/LocSvc_java(  995): got connectivity action
D/LocSvc_java(  995): broadcast - no network connections
D/LocSvc_java(  995): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  995): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  995): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  995): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  995): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/ConnectivityService(  995): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  995): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  995): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7948 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocSvc_java(  995): onReceive
D/LocSvc_java(  995): got connectivity action
D/LocSvc_java(  995): broadcast - no network connections
D/LocSvc_java(  995): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  995): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  995): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  995): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  995): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  995): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  995): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  995): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/MusicStore( 7948): Database version: 120
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7948): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7948): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7948): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7948): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7948): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7948): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7948): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7948): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b8830cd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7948): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7948): GMSCore installation verified
,I/ConfigStore( 7948): Config Database version: 1
,I/MediaRouter( 7948): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7948): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  995): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7989 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7948): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7948): Using platform SSLCertificateSocketFactory
I/ActivityManager(  995): Killing 7671:com.lge.clock/u0a10 (adj 15): empty #11
,W/ResourcesManager( 7989): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7989): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7989): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  995): failed to open /acct/uid_10010/pid_7671/cgroup.procs: No such file or directory
,I/NotificationManager( 7948): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7989): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7989): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7989): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 7916): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7916): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7916): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7916): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7916): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,D/LGDMClient( 7916): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7916): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/HubEmail( 7989): JNI_OnLoad()
I/HubEmail( 7989): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7989): registerNatives()
I/HubEmail( 7989): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7989): registerNativeMethods()
I/HubEmail( 7989): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7989): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  995): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=8023 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/Settings( 7989): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  995): Killing 7843:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10061/pid_7843/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 8023): onCreate
,W/AppUp4:DB( 8023):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 8023):  setFingerPrint start
,I/AppUp4:DB( 8023):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8023):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8023):  SDK version = 0
,I/AppUp4:DB( 8023):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8023): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 8023): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 8023): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 8023): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 8023): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 8023): onReceive
I/AppUp4:CustModeStarterReceiver( 8023): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 8023): Context : android.app.ReceiverRestrictedContext@236e7361
D/AppUp4:CustFacade( 8023): isCustomizationCompleted : false
D/AppUp4:CustFacade( 8023): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 8023): begin check event
I/AppUp4:CustModeStarterReceiver( 8023): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 8023): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 8023): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 8023): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 8023): handleAsyncCustNotification do not startCustService
I/ActivityManager(  995): Killing 7308:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 7283): android.os.DeadObjectException
,W/System.err( 7283): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7283): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7283): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7283): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7283): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7283): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7283): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7283): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7283): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7283): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7283): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7283): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7283): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7283): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7283): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7283): android.os.DeadObjectException
W/System.err( 7283): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7283): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7283): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7283): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7283): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7283): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7283): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7283): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7283): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7283): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7283): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7283): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7283): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7283): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7283): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  995): failed to open /acct/uid_10089/pid_7308/cgroup.procs: No such file or directory
W/ActivityManager(  995): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/LgeMiscReceiver( 3175): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3175): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3175): networkInfo.isConnected() = false
,I/ActivityManager(  995): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8043 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  995): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=8060 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 8060): Quickset Services start...
,I/UEI.SmartControl( 8060): Manufacture = LGE
D/UEI.SmartControl( 8060): File observer start...
,E/UEI.SmartControl( 8060): IR Port is disabled: false
D/UEI.SmartControl( 8060): Starting file observer...
D/UEI.SmartControl( 8060): Extracting JNI libs...
D/UEI.SmartControl( 8060): --- this system supports 32-bit or 64-bit only
D/PhoneMonitor( 8043): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 8043): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8043): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  995): Killing 7283:com.lge.qremote/u0a106 (adj 15): empty #11
D/PhoneMonitor( 8043): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 8043): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 8043): [parse] Load xml
V/TelephonyAutoProfiling( 8043): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 8043): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 8043): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/UEI.SmartControl( 8060): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 8060): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8060): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 8060): --- Selecting new region: 2
,I/UEI.SmartControl( 8060): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 8060): Platform has CIR...
D/UEI.SmartControl( 8060): NO CIR support, need to check package...
I/UEI.SmartControl( 8060): Model: LG-D722 uses JNI
D/UEI.SmartControl( 8060): QS Service created
W/libprocessgroup(  995): failed to open /acct/uid_10106/pid_7283/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 8060): QS start get config
,I/ActivityManager(  995): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8091 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.373ms
,D/UEI.SmartControl( 8060): Loading JNI Libs...
,D/UEI.SmartControl( 8060):  configuring local db...
D/LGWifiP2pService(  995): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  995): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.531ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.366ms
,I/ActivityManager(  995): Killing 7815:com.lge.settings.easy/1000 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_1000/pid_7815/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2682): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:18:44
D/UpdateThreadPoolManager( 2682): 2 : This is isUpdating : false
D/WeatherAncestor( 2682): connectivity changed - connection : true
D/Weather_cast( 2682): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2682): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:18:44
D/WeatherService( 2682): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/WeatherService( 2682): 2 : shouldTimeTickRegistered : false
I/ActivityManager(  995): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8112 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/UEI.SmartControl( 8060):  ---- Has DB8: true
,D/UEI.SmartControl( 8060): QS start statue = true Error code = 0
W/ResourcesManager( 8112): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/UEI.SmartControl( 8060): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 8060): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 8060): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 8060): IRRCPlayer_nativeInit ++ 
D/irrcClient( 8060): IrrcClient ++ 
D/irrcClient( 8060): getIrrcService ++ 
,D/irrcClient( 8060): getIrrcService -- 
D/irrcClient( 8060): IrrcClient -- 
W/irrc_jni( 8060): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 8060): Services init done
I/UEI.SmartControl( 8060): Device manager: loading config....
D/UEI.SmartControl( 8060): QS Service init finished
,D/UEI.SmartControl( 8060): QS Service version name: 0.1.73
D/UEI.SmartControl( 8060): QS Service version code: 1073
D/UEI.SmartControl( 8060): Service requested: Control
D/UEI.SmartControl( 8060): Config is loaded...
D/UEI.SmartControl( 8060):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 8060): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 8060): Request IControl service: devices are loaded...
D/UEI.SmartControl( 8060): Service.onUnbind: IControl
D/UEI.SmartControl( 8060): Service.onDestroy
D/UEI.SmartControl( 8060): Shutdown IRRCPlayer... 
W/irrc_jni( 8060): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 8060): ~IrrcClient ++ 
D/irrcClient( 8060): ~IrrcClient -- 
W/irrc_jni( 8060): IRRCPlayer_nativeFinalize -- 
,D/UEI.SmartControl( 8060): Blaster closed
D/UEI.SmartControl( 8060): Blaster closed
D/UEI.SmartControl( 8060): Shut down QS...
D/UEI.SmartControl( 8060): Stopped file observer...
I/UEI.SmartControl( 8060): QS lib stop result = true
D/UEI.SmartControl( 8060): QS shutdown complete
D/UEI.SmartControl( 8060): QS Service created
E/UEI.SmartControl( 8060): QS start get config
,D/UEI.SmartControl( 8060):  configuring local db...
I/Babel_SMS( 8112): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8112): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8112): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 8112): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8112): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8112): MmsConfig.loadFromResources
E/Babel_SMS( 8112): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8112): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 8112): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 8112): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 8112): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 8112): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 8112): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 8112): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 8112): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 8112): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 8112): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 8112): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 8112): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 8112): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 8112): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 8112): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 8112): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 8112): found sensor: Motion Accel, handle=46
W/Settings( 8112): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8112): startup - clean
I/Babel   ( 8112): deleted: false for 0
,I/art     ( 8112): CheckpointMarkThreadRoots callback created = 0xb04556a0
,D/UEI.SmartControl( 8060):  ---- Has DB8: true
,D/UEI.SmartControl( 8060): QS start statue = true Error code = 0
D/UEI.SmartControl( 8060): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 8060): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 8060): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 8060): IRRCPlayer_nativeInit ++ 
D/irrcClient( 8060): IrrcClient ++ 
D/irrcClient( 8060): getIrrcService ++ 
D/irrcClient( 8060): getIrrcService -- 
D/irrcClient( 8060): IrrcClient -- 
W/irrc_jni( 8060): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 8060): Services init done
I/art     ( 8112): CheckpointMarkThreadRoots callback created = 0xb0455670
I/UEI.SmartControl( 8060): Device manager: loading config....
D/UEI.SmartControl( 8060): Config is loaded...
I/ActivityManager(  995): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8150 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 8060): QS Service init finished
,D/PowerManagerServiceEx(  995): acquireWakeLockInternal: lock=1051057766, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=995
,V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{2d579e8 type 2 when 471354 com.google.android.gms} when 471354
,D/UEI.SmartControl( 8060):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 8060): Notify AllClients services are ready: 0
D/UEI.SmartControl( 8060): QS Service version name: 0.1.73
D/UEI.SmartControl( 8060): QS Service version code: 1073
D/UEI.SmartControl( 8060): Service requested: Control
,I/ActivityManager(  995): Killing 7767:com.android.settings/1000 (adj 15): empty #11
W/AudioCapabilities( 8112): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 8112): Unsupported mime audio/adpcm
W/AudioCapabilities( 8112): Unsupported mime audio/g726
W/AudioCapabilities( 8112): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 8112): Unsupported mime audio/wma-voice
W/VideoCapabilities( 8112): Unsupported mime video/mjpg
,W/VideoCapabilities( 8112): Unsupported mime video/theora
W/AudioCapabilities( 8112): Unsupported mime audio/evrc
,W/AudioCapabilities( 8112): Unsupported mime audio/qcelp
W/VideoCapabilities( 8112): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 8112): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 8112): Unsupported mime audio/qcelp
W/AudioCapabilities( 8112): Unsupported mime audio/evrc
W/VideoCapabilities( 8112): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 8112): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8112): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8112): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8112): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8112): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  995): failed to open /acct/uid_1000/pid_7767/cgroup.procs: No such file or directory
,E/ActivityThread( 8060): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@2733f774 that was originally bound here
E/ActivityThread( 8060): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@2733f774 that was originally bound here
E/ActivityThread( 8060): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 8060): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 8060): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 8060): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 8060): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 8060): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 8060): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 8060): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 8060): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 8060): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 8060): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 8060): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 8060): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 8060): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 8060): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 8060): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 8060): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 8060): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 8060): Internal service binding...
I/vclib   ( 8112): onServiceConnected
W/Babel   ( 8112): Attempted to change video mute state without an active call.
,I/Babel   ( 8112): connection state changed from UNKNOWN to DISCONNECTED
I/NotificationManager( 8112): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  995): Killing 7797:com.lge.sync/1000 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_1000/pid_7797/cgroup.procs: No such file or directory
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8150): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 8150): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8150):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8150):   adb logcat -s GAv4
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8150): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8150): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8150): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 8150): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8150): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8150): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 8150): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8150): Time to load native libraries: 1 ms (timestamps 2091-2092)
I/LibraryLoader( 8150): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8150): Binding Chromium to main looper Looper (main, tid 1) {e5d519c}
,I/LibraryLoader( 8150): Expected native library version number "",actual native library version number ""
I/chromium( 8150): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8150): Initializing chromium process, singleProcess=true
W/art     ( 8150): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 8150): ApplicationContext is null in ApplicationStatus
W/chromium( 8150): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8150): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8150): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 8150): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8150): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8150): Build Date: 03/02/15 Mon
I/Adreno-EGL( 8150): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 8150): Remote Branch: 
I/Adreno-EGL( 8150): Local Patches: 
I/Adreno-EGL( 8150): Reconstruct Branch: 
I/NSApplication( 8150): Starting up...
,V/AudioPolicyService(  278): registerClient() client 0xb40277a0, uid 10079
W/AudioManagerAndroid( 8150): Requires BLUETOOTH permission
I/ActivityManager(  995): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8216 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  995): Killing 7948:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_10081/pid_7948/cgroup.procs: No such file or directory
,I/art     (  995): Explicit concurrent mark sweep GC freed 26276(1348KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.097ms total 139.384ms
,I/ActivityManager(  995): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8243 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  995): Killing 7989:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_10021/pid_7989/cgroup.procs: No such file or directory
,W/ResourcesManager( 8243): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 4245): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ActivityManager(  995): Killing 7916:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/iu.UploadsManager( 4245): num queued entries: 0
I/iu.UploadsManager( 4245): num updated entries: 0
,I/iu.SyncManager( 4245): NEXT; no task
W/libprocessgroup(  995): failed to open /acct/uid_1000/pid_7916/cgroup.procs: No such file or directory
,I/ActivityManager(  995): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8267 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 8267): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8267): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8267): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8267): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 8267): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8267): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8267): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8267): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8267): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b8830cd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8267): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 8267): GMSCore installation verified
I/ConfigStore( 8267): Config Database version: 1
,I/MediaRouter( 8267): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8267): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  995): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8296 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 8267): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8267): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 8296): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8296): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 8296): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  995): Killing 8023:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10011/pid_8023/cgroup.procs: No such file or directory
,I/LGEmail ( 8296): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/NotificationManager( 8267): com.google.android.music: cancel(1061) by com.google.android.music
D/LGEmail ( 8296): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 8296): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  995): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=8323 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 8296): JNI_OnLoad()
I/HubEmail( 8296): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 8296): registerNatives()
I/HubEmail( 8296): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 8296): registerNativeMethods()
I/HubEmail( 8296): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 8296): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  995): Killing 8043:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,W/libprocessgroup(  995): failed to open /acct/uid_10038/pid_8043/cgroup.procs: No such file or directory
W/Settings( 8296): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 8323): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 8323): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 8323): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 8323): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 8323): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 8323): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 8323): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/ActivityManager(  995): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=8346 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  995): Killing 8091:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_10051/pid_8091/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 8346): onCreate
,W/AppUp4:DB( 8346):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 8346):  setFingerPrint start
I/AppUp4:DB( 8346):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8346):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8346):  SDK version = 0
I/AppUp4:DB( 8346):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 8346): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 8346): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 8346): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 8346): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 8346): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 8346): onReceive
I/AppUp4:CustModeStarterReceiver( 8346): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 8346): Context : android.app.ReceiverRestrictedContext@236e7361
D/AppUp4:CustFacade( 8346): isCustomizationCompleted : false
D/AppUp4:CustFacade( 8346): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 8346): begin check event
I/AppUp4:CustModeStarterReceiver( 8346): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 8346): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 8346): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 8346): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 8346): handleAsyncCustNotification do not startCustService
I/ActivityManager(  995): Killing 8060:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_10089/pid_8060/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3175): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3175): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3175): networkInfo.isConnected() = false
I/ActivityManager(  995): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8368 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8368): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 8368): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8368): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  995): Killing 8112:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 8368): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 8368): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 8368): [parse] Load xml
V/TelephonyAutoProfiling( 8368): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 8368): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 8368): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  995): failed to open /acct/uid_10061/pid_8112/cgroup.procs: No such file or directory
,I/ActivityManager(  995): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8387 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  995): Killing 8150:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,D/WeatherAncestor( 2682): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:18:48
,W/libprocessgroup(  995): failed to open /acct/uid_10079/pid_8150/cgroup.procs: No such file or directory
D/UpdateThreadPoolManager( 2682): 2 : This is isUpdating : false
D/WeatherAncestor( 2682): connectivity changed - connection : true
D/Weather_cast( 2682): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2682): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:18:48
D/WeatherService( 2682): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/WeatherService( 2682): 2 : shouldTimeTickRegistered : false
I/ActivityManager(  995): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8404 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 25.175ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.219ms
,W/ResourcesManager( 8404): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.898ms
,I/Babel_SMS( 8404): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8404): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8404): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 8404): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8404): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 8404): MmsConfig.loadFromResources
E/Babel_SMS( 8404): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8404): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 8404): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 8404): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 8404): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 8404): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 8404): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 8404): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 8404): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 8404): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 8404): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 8404): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 8404): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 8404): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 8404): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 8404): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 8404): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 8404): found sensor: Motion Accel, handle=46
,W/Settings( 8404): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 8404): startup - clean
,I/Babel   ( 8404): deleted: false for 0
,I/art     ( 8404): CheckpointMarkThreadRoots callback created = 0xb042d590
,I/art     ( 8404): CheckpointMarkThreadRoots callback created = 0xb042d570
,I/ActivityManager(  995): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8440 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 8404): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 8404): Unsupported mime audio/adpcm
W/AudioCapabilities( 8404): Unsupported mime audio/g726
,W/AudioCapabilities( 8404): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 8404): Unsupported mime audio/wma-voice
D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 475316317635; DSPS: 15673844; Offset : -3022700032
W/VideoCapabilities( 8404): Unsupported mime video/mjpg
W/VideoCapabilities( 8404): Unsupported mime video/theora
W/AudioCapabilities( 8404): Unsupported mime audio/evrc
,W/AudioCapabilities( 8404): Unsupported mime audio/qcelp
W/VideoCapabilities( 8404): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 8404): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 8404): Unsupported mime audio/qcelp
W/AudioCapabilities( 8404): Unsupported mime audio/evrc
W/VideoCapabilities( 8404): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 8404): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8404): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8404): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8404): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8404): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 8404): onServiceConnected
,W/Babel   ( 8404): Attempted to change video mute state without an active call.
I/Babel   ( 8404): connection state changed from UNKNOWN to DISCONNECTED
I/NotificationManager( 8404): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  995): Killing 8216:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10048/pid_8216/cgroup.procs: No such file or directory
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 8440): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8440):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8440):   adb logcat -s GAv4
W/GAv4    ( 8440): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8440): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8440): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  995): Failed to find a new network - expiring NetTransition Wakelock
,I/WebViewFactory( 8440): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8440): Time to load native libraries: 2 ms (timestamps 5809-5811)
I/LibraryLoader( 8440): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8440): Binding Chromium to main looper Looper (main, tid 1) {e5d519c}
I/LibraryLoader( 8440): Expected native library version number "",actual native library version number ""
I/chromium( 8440): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8440): Initializing chromium process, singleProcess=true
W/art     ( 8440): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8440): ApplicationContext is null in ApplicationStatus
,W/chromium( 8440): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8440): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8440): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 8440): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8440): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8440): Build Date: 03/02/15 Mon
I/Adreno-EGL( 8440): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 8440): Remote Branch: 
I/Adreno-EGL( 8440): Local Patches: 
I/Adreno-EGL( 8440): Reconstruct Branch: 
V/AudioPolicyService(  278): registerClient() client 0xb57ea3a0, uid 10079
,W/AudioManagerAndroid( 8440): Requires BLUETOOTH permission
I/NSApplication( 8440): Starting up...
I/ActivityManager(  995): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8503 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  995): Killing 8243:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  995): failed to open /acct/uid_10086/pid_8243/cgroup.procs: No such file or directory
,I/ActivityManager(  995): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8525 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  995): Killing 8267:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10081/pid_8267/cgroup.procs: No such file or directory
W/ResourcesManager( 8525): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  995): Killing 8296:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_10021/pid_8296/cgroup.procs: No such file or directory
,I/art     (  995): Explicit concurrent mark sweep GC freed 14155(711KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.106ms total 182.657ms
,D/PowerManagerServiceEx(  995): releaseWakeLockInternal: lock=1051057766 [*alarm*], flags=0x0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  995): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/PowerManagerServiceEx(  995): acquireWakeLockInternal: lock=1051057766, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=995
,V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{101535c8 type 2 when 488003 com.google.android.gms} when 488003
D/PowerManagerServiceEx(  995): releaseWakeLockInternal: lock=1051057766 [*alarm*], flags=0x0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  995): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 495316998617; DSPS: 16329227; Offset : -3022720875
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{301b0661 type 2 when 510737 com.google.android.gms} when 510737
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  995): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 515317682828; DSPS: 16984609; Offset : -3022707921
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 535318456727; DSPS: 17639995; Offset : -3022727687
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 555319184427; DSPS: 18295379; Offset : -3022732148
,D/PowerManagerServiceEx(  995): acquireWakeLockInternal: lock=1051057766, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=995
,V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{7797586 type 2 when 556153 com.google.android.gms} when 556153
D/PowerManagerServiceEx(  995): releaseWakeLockInternal: lock=1051057766 [*alarm*], flags=0x0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  995): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 575319955826; DSPS: 18950764; Offset : -3022723507
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 595320758840; DSPS: 19606150; Offset : -3022714262
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 615321540759; DSPS: 20261536; Offset : -3022725513
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 635322311273; DSPS: 20916921; Offset : -3022718277
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  995): acquireWakeLockInternal: lock=1051057766, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=995
,V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{1c2a0e47 type 2 when 646975 com.google.android.gms} when 646975
,D/PowerManagerServiceEx(  995): releaseWakeLockInternal: lock=1051057766 [*alarm*], flags=0x0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  995): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 655323009442; DSPS: 21572304; Offset : -3022721909
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 675323852715; DSPS: 22227691; Offset : -3022702740
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 695324635520; DSPS: 22883077; Offset : -3022713497
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 715325508741; DSPS: 23538465; Offset : -3022694560
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 735326380816; DSPS: 24193854; Offset : -3022707651
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 755327058101; DSPS: 24849237; Offset : -3022732062
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 775327934916; DSPS: 25504625; Offset : -3022709791
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 795328709909; DSPS: 26160011; Offset : -3022728360
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 815329472193; DSPS: 26815396; Offset : -3022728753
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  995): acquireWakeLockInternal: lock=1051057766, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=995
,V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{202be674 type 2 when 828583 com.google.android.gms} when 828583
D/PowerManagerServiceEx(  995): releaseWakeLockInternal: lock=1051057766 [*alarm*], flags=0x0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  995): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 835330565102; DSPS: 27470791; Offset : -3022704300
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 855331333168; DSPS: 28126177; Offset : -3022729482
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 875332190660; DSPS: 28781565; Offset : -3022726743
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 895333084037; DSPS: 29436954; Offset : -3022718479
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 915333913509; DSPS: 30092341; Offset : -3022712695
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 935334612251; DSPS: 30747724; Offset : -3022715832
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 955335396306; DSPS: 31403110; Offset : -3022725312
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 975336258486; DSPS: 32058498; Offset : -3022717780
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 995337123530; DSPS: 32713886; Offset : -3022707203
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1015337913835; DSPS: 33369272; Offset : -3022710277
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1035338715390; DSPS: 34024658; Offset : -3022702309
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1055339489236; DSPS: 34680044; Offset : -3022722024
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1075340782771; DSPS: 35335446; Offset : -3022709914
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1095341468961; DSPS: 35990829; Offset : -3022725707
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1115342241506; DSPS: 36646214; Offset : -3022716179
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1135343095977; DSPS: 37301602; Offset : -3022716018
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,D/WifiController(  995): battery changed pluggedType: 2
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1155343848209; DSPS: 37956987; Offset : -3022726856
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1175344525806; DSPS: 38612369; Offset : -3022720593
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  995): acquireWakeLockInternal: lock=1051057766, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=995
,V/AlarmManager(  995): ELAPSED_WAKEUP set : Alarm{4a0a79d type 2 when 1191766 com.google.android.gms} when 1191766
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  995): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager(  995): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8671 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 8671): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8671): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@348070ba
D/PowerManagerServiceEx(  995): releaseWakeLockInternal: lock=1051057766 [*alarm*], flags=0x0
I/ActivityManager(  995): Killing 8323:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  995): failed to open /acct/uid_1000/pid_8323/cgroup.procs: No such file or directory
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1195345388142; DSPS: 39267757; Offset : -3022712620
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1215346069957; DSPS: 39923140; Offset : -3022732892
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  995): User[0] Flushing usage stats to disk
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1235346755887; DSPS: 40578522; Offset : -3022718427
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1255347511921; DSPS: 41233907; Offset : -3022725227
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1275348270194; DSPS: 41889292; Offset : -3022729919
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1295349048885; DSPS: 42544677; Offset : -3022714169
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1315349719606; DSPS: 43200059; Offset : -3022714627
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1335350741683; DSPS: 43855453; Offset : -3022730380
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1355351415893; DSPS: 44510835; Offset : -3022727479
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1375352096302; DSPS: 45166217; Offset : -3022718484
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1395352859628; DSPS: 45821602; Offset : -3022718018
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1415353639516; DSPS: 46476987; Offset : -3022701018
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1435354292581; DSPS: 47132369; Offset : -3022719131
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1455354963980; DSPS: 47787751; Offset : -3022719171
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1475355639181; DSPS: 48443133; Offset : -3022715383
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1495356408392; DSPS: 49098518; Offset : -3022708955
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1515357089634; DSPS: 49753901; Offset : -3022729930
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1535357865720; DSPS: 50409286; Offset : -3022716575
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1555358538786; DSPS: 51064668; Offset : -3022715000
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1575359327632; DSPS: 51720054; Offset : -3022719663
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1595360431635; DSPS: 52375450; Offset : -3022714450
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1615361209544; DSPS: 53030836; Offset : -3022729998
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1635361972766; DSPS: 53686221; Offset : -3022729532
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1655362647029; DSPS: 54341603; Offset : -3022726812
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1675363402959; DSPS: 54996988; Offset : -3022733717
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/WifiController(  995): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1695364075190; DSPS: 55652370; Offset : -3022732717
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1715364929975; DSPS: 56307758; Offset : -3022732555
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1735365604238; DSPS: 56963140; Offset : -3022729965
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  995): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1755366270792; DSPS: 57618522; Offset : -3022734667
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1775366950004; DSPS: 58273904; Offset : -3022726763
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1795367631246; DSPS: 58929286; Offset : -3022716908
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  995): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  995): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1815368479624; DSPS: 59584674; Offset : -3022723022
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1835369150866; DSPS: 60240056; Offset : -3022723272
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1855369833254; DSPS: 60895438; Offset : -3022712244
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  995): battery changed pluggedType: 2
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1875370652102; DSPS: 61550825; Offset : -3022717397
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  995): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  995): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  995): tsOffsetIs: Apps: 1895371361000; DSPS: 62206208; Offset : -3022710404
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8788): 
D/AndroidRuntime( 8788): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8788): CheckJNI is OFF
D/AndroidRuntime( 8788): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  995): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  995): Killing 6055:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  995): WIN DEATH: Window{231a88be u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  995): Skipping PackageSetting{1124bd45 com.example.hello/10030} due to missing metadata
D/InputDispatcher(  995): Focus left window: Window{231a88be u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  995): Window went away: Window{231a88be u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  995):   Force finishing activity ActivityRecord{2124544d u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  995): Display changed displayId=0
D/DSDPConnection( 1753): Display #0 changed.
W/ActivityManager(  995): Spurious death for ProcessRecord{29ef47e3 6055:com.test.thalitest/u0a316}, curProc for 6055: null
I/ProcessStatsService(  995): Prepared write state in 13ms
I/ActivityManager(  995): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  995):   Force finishing activity ActivityRecord{2124544d u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  995): Duplicate finish request for ActivityRecord{2124544d u0 com.test.thalitest/.MainActivity t220 f}
I/[LGHome]EVENT( 1879): [Launcher.java:5203:onStart()]onStart
I/[LGHome]EVENT( 1879): [Launcher.java:776:onResume()]onResume
I/ProcessStatsService(  995): Prepared write state in 10ms
I/[LGHome]EVENT( 1879): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/[LGHome]LGActivityUtil( 1879): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/art     ( 1964): Explicit concurrent mark sweep GC freed 9787(665KB) AllocSpace objects, 4(95KB) LOS objects, 40% free, 11MB/19MB, paused 3.409ms total 88.399ms
I/QCNEJ   ( 1841): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3618): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/InputReader(  995): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3618): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3618): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3618): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3618): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3618): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3618): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3618): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3618): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3618): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3618): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3618): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1734): Ignoring removeGeofence because network location is disabled.
I/art     ( 4245): Explicit concurrent mark sweep GC freed 5770(329KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 13MB/18MB, paused 2.549ms total 126.510ms
I/ActivityManager(  995): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8821 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1879): [Launcher.java:929:onResume()]onResume end
I/Activity( 1879): Activity.onPostResume() called 
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
W/[LGHome]LGWallpaperInfo( 1879): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1879): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework](  995): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  995): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  995): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  995): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  995): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@306ef261,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  995): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  995): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/InputDispatcher(  995): Focus entered window: Window{21c4309e u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  995): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  995): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  995): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  995): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@306ef261,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  995): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/art     (  995): Explicit concurrent mark sweep GC freed 30635(2MB) AllocSpace objects, 9(249KB) LOS objects, 33% free, 23MB/34MB, paused 5.706ms total 228.845ms
I/art     (  995): WaitForGcToComplete blocked for 154.537ms for cause Explicit
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1879): [setNavigationBarColor] color=0x 0
I/ActivityManager(  995): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8841 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 8821): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8821): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8821): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/administrator(  995): Handling package changes for user 0
W/InputMethodManagerService(  995): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  995): Got RemoteException sending setActive(false) notification to pid 6055 uid 10316
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/LockScreenSettings( 8841): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline(  995): Timeline: Activity_windows_visible id: ActivityRecord{3ac5eb56 u0 com.lge.launcher2/.Launcher t219} time:1908044
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
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
I/ActivityManager(  995): Killing 8346:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/IInputConnectionWrapper( 1879): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
E/b       ( 1611): Unable to connect to the editor to retrieve text... will retry later
I/LGEmail ( 8821): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 8821): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/NotificationService(  995): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  995): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  995): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  995): Explicit concurrent mark sweep GC freed 5494(330KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 10.842ms total 351.790ms
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
D/KeyguardModel( 1374): handleShortcutListChanged...
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/libprocessgroup(  995): failed to open /acct/uid_10011/pid_8346/cgroup.procs: No such file or directory
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  995): removeObsoleteFile: deleting file=220_task.xml
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): handleShortcutListChanged...
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/ProcessStatsService(  995): Pruning old procstats: /data/system/procstats/state-2015-12-09-03-33-24.bin
D/AndroidRuntime( 8788): Shutting down VM
I/PackageChangeReceiver( 8821): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  995): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8864 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  995): Killing 8368:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
W/libprocessgroup(  995): failed to open /acct/uid_10038/pid_8368/cgroup.procs: No such file or directory
E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/AppUp4:AppBoxCP( 8864): onCreate
W/AppUp4:DB( 8864):  [AppBoxDatabaseHelper] construct
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1879): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/AppUp4:DB( 8864):  setFingerPrint start
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/AppUp4:DB( 8864):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/AppUp4:DB( 8864):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8864):  SDK version = 0
I/AppUp4:DB( 8864):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8864): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 8864): added Exclude : com.test.thalitest
I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  995): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8883 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/ActivityManager(  995): Killing 8387:com.lge.drmservice/u0a51 (adj 15): empty #11
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  995): failed to open /acct/uid_10051/pid_8387/cgroup.procs: No such file or directory
E/SharedPreferencesImpl( 1879): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak

```
