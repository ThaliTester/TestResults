#### Test 5497026179923a9_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/GAV2    ( 5852): Thread[GAThread,5,main]: No campaign data found.
D/AndroidRuntime( 6116): 
D/AndroidRuntime( 6116): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6116): CheckJNI is OFF
D/AndroidRuntime( 6116): Calling main entry com.android.commands.am.Am
--------- beginning of system
W/ActivityManager(  859): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  859): RTC_WAKEUP set : Alarm{3ed384bd type 0 when 1452509353912 com.android.providers.contacts} when 1452509353912
V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{19af4ab2 type 2 when 60352 com.google.android.talk} when 60352
D/Finsky  ( 6022): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/ActivityManager(  859): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/AlarmManager(  859): RTC_WAKEUP set : Alarm{3b8afb9 type 0 when 1452509411096 com.android.vending} when 1452509411096
D/ActivityManager(  859): setTaskToReturnTo : TaskRecord{1963735f #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  859): setTaskToReturnTo : TaskRecord{1963735f #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  859): AppWindowTokenEx init.. 
D/ContextHelper(  859): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  859): Focus left window: Window{33c5b97 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6116): Shutting down VM
D/SplitWindow(  859): check instance of lgWin Window{152bc462 u0 Starting com.test.thalitest}
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  859): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6142 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  859): android: cancelAsUser(2) by android
I/HotwordDetector( 1940): Closing mic
I/MicrophoneInputStream( 1940): mic_close com.google.android.apps.gsa.speech.audio.u@114d44a8
V/AudioRecord( 1940): stop()
D/AudioRecord( 1940): AudioRecord->stop()
V/AudioFlinger(  289): RecordHandle::stop()
V/AudioFlinger(  289): RecordThread::stop
V/AudioFlinger(  289): Record stopped OK
V/AudioPolicyManager(  289): stopInput() input 17
V/AudioPolicyService(  289): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  289): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  289): AudioCommandThread() waking up
V/AudioPolicyService(  289): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  289): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  289): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  289): ThreadBase::setParameters() routing=0
V/AudioFlinger(  289): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  289): processConfigEvents_l() remaining events 1
V/AudioFlinger(  289): processConfigEvents_l() DONE thread 0xb4393000
D/audio_hw_primary(  289): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 94799215072; DSPS: 3204282; Offset : -2998711143
I/WindowStateAnimator(  859): Starting window displayed
I/SystemUI[Framework](  859): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  859): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  859): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  859): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3555b1f3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
V/audio_hw_primary(  289): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  289): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  289): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  289): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  289): disable_audio_route: exit
E/audio_hw_primary(  289): disable_snd_device: enter 144
D/hardware_info(  289): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  289): disable_snd_device: snd_device(144: lg-vr-handset-mic)
,I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
V/audio_hw_primary(  289): stop_input_stream: exit: status(0)
V/audio_hw_primary(  289): in_standby: exit:  status(0)
V/AudioFlinger(  289): RecordThread: loop stopping
V/AudioPolicyService(  289): AudioCommandThread() going to sleep
V/AudioPolicyManager(  289): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  289): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  289): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  289): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  289): AudioCommandThread() waking up
V/AudioPolicyService(  289): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  289): AudioCommandThread() going to sleep
V/AudioPolicyService(  289): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  289): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  289): AudioCommandThread() waking up
V/AudioPolicyService(  289): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  289): setParameters(): io 17, keyvalue hotword_active=0, calling pid 289
V/AudioFlinger(  289): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  289): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  289): RecordThread: loop starting
V/AudioFlinger(  289): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  289): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  289): in_set_parameters: exit: status(0)
V/AudioFlinger(  289): processConfigEvents_l() DONE thread 0xb4393000
V/AudioFlinger(  289): RecordThread: loop stopping
D/BarTransitions( 1375): draw background and invalidate : color = 1c000000
V/AudioPolicyService(  289): AudioCommandThread() going to sleep
D/BarTransitions( 1375): draw background and invalidate : color = 16161616
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
D/AlertService( 5943): Beginning updateAlertNotification
V/AudioFlinger(  289): RecordHandle::stop()
V/AudioFlinger(  289): RecordThread::stop
V/AudioPolicyManager(  289): releaseInput() 17
V/AudioPolicyManager(  289): closeInput(17)
V/AudioFlinger(  289): closeInput() 17
V/AudioSystem(  289): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  859): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1375): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1753): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  289): ThreadBase::exit
V/AudioFlinger(  289): RecordThread: loop starting
V/AudioSystem( 2007): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  289): releasing 16 from 1940 for -1
V/AudioFlinger(  289):  decremented refcount to 0
V/AudioFlinger(  289): purging stale effects
V/AudioFlinger(  289): RecordThread 0xb4393000 exiting
V/AudioSystem( 1940): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  289): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  289): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  289): in_standby: exit:  status(0)
V/AudioSystem( 3180): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2592): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  289): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  289): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  289): releaseInput() exit
V/AudioPolicyService(  289): AudioCommandThread() waking up
V/AudioPolicyService(  289): AudioCommandThread() processing update audio port list
V/AudioFlinger(  289): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  289): removeClient_l() pid 1940, calling pid 289
V/AudioPolicyService(  289): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1940): Stopping hotword detection.
I/HotwordRecognitionRnr( 1940): Hotword detection finished
D/AlertService( 5943): No fired or scheduled alerts
I/NotificationManager( 5943): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(9) by com.android.calendar
D/libc-netbsd( 6022): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6022): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6022): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6022): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  283): App 10036 tries DNS query. Accept family:0 protocol:0
I/NotificationManager( 5943): com.android.calendar: cancel(10) by com.android.calendar
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
I/NotificationManager( 5943): com.android.calendar: cancel(11) by com.android.calendar
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=1, netid=100
I/NotificationManager( 5943): com.android.calendar: cancel(12) by com.android.calendar
D/libc-netbsd(  283): res_queryN name = xxxxx, class = 1, type = 1
I/NotificationManager( 5943): com.android.calendar: cancel(13) by com.android.calendar
D/libc-netbsd(  283): res_queryN name = xxxxx succeed
I/System.out( 6022): propertyValue:false
I/NotificationManager( 5943): com.android.calendar: cancel(14) by com.android.calendar
D/libc-netbsd( 6022): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6022): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager( 5943): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5943): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5943): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/ContextHelper( 6142): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/AlarmScheduler( 5943): No events found starting within 1 week.
I/WebViewFactory( 6142): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/libc-netbsd( 6022): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6022): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/LibraryLoader( 6142): Time to load native libraries: 2 ms (timestamps 5144-5146)
I/LibraryLoader( 6142): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6142): Binding Chromium to main looper Looper (main, tid 1) {cb5a10}
I/LibraryLoader( 6142): Expected native library version number "",actual native library version number ""
I/chromium( 6142): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6142): Initializing chromium process, singleProcess=true
W/art     ( 6142): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6142): ApplicationContext is null in ApplicationStatus
W/chromium( 6142): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6142): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6142): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6142): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6142): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6142): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6142): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6142): Remote Branch: 
I/Adreno-EGL( 6142): Local Patches: 
I/Adreno-EGL( 6142): Reconstruct Branch: 
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  859): android: cancelAsUser(2) by android
I/qtaguid ( 6022): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6022): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6022): untagSocket(41) failed with errno -22
D/Finsky  ( 6022): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
V/AudioPolicyService(  289): registerClient() client 0xb551cde0, uid 10316
D/BluetoothManagerService(  859): Message: 20
D/BluetoothManagerService(  859): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@73e67d1:true
,D/BluetoothAdapterService(32769852)( 2007): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@15aa5e72
I/ActivityManager(  859): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6195 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,W/art     ( 6142): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6142): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6142): CordovaWebView is running on device made by: LGE
,W/ResourcesManager( 6195): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6195): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/art     ( 6142): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6142): Attempt to remove local handle scope entry from IRT, ignoring
I/MultiDex( 6195): VM with version 2.1.0 has multidex support
I/MultiDex( 6195): install
I/MultiDex( 6195): VM has multidex support, MultiDex support library is disabled.
,I/Activity( 6142): Activity.onPostResume() called 
D/OpenGLRenderer( 6142): Render dirty regions requested: true
I/OpenGLRenderer( 6142): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6142): Enabling debug mode 0
,D/Atlas   ( 6142): Validating map...
,D/SplitWindow(  859): check instance of lgWin Window{3a5944ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
V/JNIHelp ( 6195): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/chromium( 6142): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  859): Focus entered window: Window{3a5944ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/qtaguid ( 6022): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6022): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6022): untagSocket(41) failed with errno -22
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/InputMethodManagerService(  859): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  859): Displayed com.test.thalitest/.MainActivity: +1s238ms
I/Timeline(  859): Timeline: Activity_windows_visible id: ActivityRecord{36f941ac u0 com.test.thalitest/.MainActivity t220} time:95891
,I/Timeline( 6142): Timeline: Activity_idle id: android.os.BinderProxy@2d85281f time:95897
W/ActivityThread( 6195): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6195): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ce1fdd2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6195): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6195): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6195): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1735): callingUid 10006, callindPid: 1735
E/MDM     ( 1735): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 6195): Reading stored module config
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4217): Restart initialization of location
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,D/ChimeraCfgMgr( 6195): Loading module com.google.android.gms.car from APK com.google.android.gms
W/BindingManager( 6142): Cannot call determinedVisibility() - never saw a connection for the pid: 6142
,D/NativeLibraryUtils( 6195): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6195): Connecting to CarCallService...
I/art     ( 6195): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6195): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6022): CheckpointMarkThreadRoots callback created = 0xb0562370
,D/CAR.SERVICE( 6195): com.google.android.projection.gearhead isn't installed.
,I/art     ( 6022): CheckpointMarkThreadRoots callback created = 0xb0562350
,D/CAR.TEL.Service( 6195): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6195): Creating a new PhoneAdapter instance
W/ActivityManager(  859): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6195): setListener: com.google.android.gms.car.dn@4b0c6c9
,W/ActivityManager(  859): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6195): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6195): Starting CarCallService with initial phone null
I/NotificationManager( 6195): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6195): Package validated; name: com.android.vending
,I/NotificationManager( 6022): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6022): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/JsMessageQueue( 6142): Set native->JS mode to OnlineEventsBridgeMode
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/jxcore_app_log( 6142): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622836224
,D/JX-Cordova( 6142): jxcore cordova android initializing
I/art     ( 6142): CheckpointMarkThreadRoots callback created = 0x9bde7470
,I/art     ( 6142): CheckpointMarkThreadRoots callback created = 0x9bde7440
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,I/qtaguid ( 6022): Failed write_ctrl(u 41) res=-1 errno=22
,I/qtaguid ( 6022): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6022): untagSocket(41) failed with errno -22
W/ResourcesManager( 6022): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6022): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6022): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6022): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  859): RTC_WAKEUP set : Alarm{3fc55a82 type 0 when 1452509414396 com.android.vending} when 1452509414396
,D/Finsky  ( 6022): [760] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1735): client connected with version: 8296000
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Finsky  ( 6022): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6022): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 6022): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6022): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6022): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6022): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  283): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  283): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  283): res_queryN name = xxxxx succeed
,I/System.out( 6022): propertyValue:false
I/ActivityManager(  859): Process com.android.contacts (pid 5783) has died
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,W/jxcore-log( 6142): Initializing JXcore engine
,W/jxcore-log( 6142): JXcore engine is ready
W/jxcore-log( 6142): Starting JXcore engine
,W/.test.thalitest( 6142): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8531]" dev="sockfs" ino=8531 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6142): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6142): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8653]" dev="sockfs" ino=8653 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6142): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6142): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6142): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[28038]" dev="sockfs" ino=28038 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6142): Platform android
W/jxcore-log( 6142): 
W/jxcore-log( 6142): Process ARCH arm
W/jxcore-log( 6142): 
,I/ActivityManager(  859): Process com.google.android.gm (pid 5852) has died
,V/AlarmManager(  859): RTC_WAKEUP set : Alarm{3ceba2e8 type 0 when 1452509416451 com.google.android.googlequicksearchbox} when 1452509416451
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/jxcore-log( 6142): JXcore Cordova bridge is ready!
I/jxcore-log( 6142): 
,W/jxcore-log( 6142): JXcore engine is started
I/Choreographer( 6142): Skipped 194 frames!  The application may be doing too much work on its main thread.
I/chromium( 6142): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 6142): Toggling radios to true
I/jxcore-log( 6142): 
,D/BluetoothAdapter( 6142): enable(): BT is already enabled..!
D/WifiServiceImplEx(  859): setWifiEnabled: true pid=6142, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  859): setWifiEnabled: true pid=6142, uid=10316
D/WifiServiceImplEx(  859): disconnect pid=6142, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  859): reconnect pid=6142, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6142): Radios toggled
I/jxcore-log( 6142): 
,I/jxcore-log( 6142): My device name is: LGE-LG-D722
I/jxcore-log( 6142): 
I/Netd    (  283): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2692): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/wpa_supplicant( 2692): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/Netd    (  283): M: Get netlink event, ifname: wlan0 action: 4
,E/WifiStateMachine(  859): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  859): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WfdsMonitor( 1807): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService(  859): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  859): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  859): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  283): Clearing all IP addresses on wlan0
,I/Netd    (  283): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1735): Read error: ssl=0xaaede800: I/O error during system call, Connection timed out
V/NativeCrypto( 1735): SSL shutdown failed: ssl=0xaaede800: I/O error during system call, Broken pipe
,D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  283): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  283): M: Get netlink event, ifname: wlan0 action: 7
D/ConnectivityService(  859): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  859): ignoring duplicate network state non-change
D/WifiHS20(  859): hidePasspointNotification off =false
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  859): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:17.155 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  859): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): ValidatedState{ when=-7ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): DefaultState{ when=-17ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): Forcing reevaluation
,D/WifiServiceExtension( 1807): isInternetCheckAvailable return false
,I/ActivityManager(  859): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6300 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
E/WifiStateMachine(  859): Start Disconnecting Watchdog 1
,D/WifiHS20(  859): hidePasspointNotification off =false
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/wpa_supplicant( 2692): wlan0: CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService(  859): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  859): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:17.246 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/CommandListener(  283): Clearing all IP addresses on wlan0
,D/ConnectivityService(  859): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  859): disableDataServiceNotify
D/DSQN    (  859): stop dsqn bin
D/WifiHS20(  859): hidePasspointNotification off =false
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:17.267 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1807): isInternetCheckAvailable return false
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/WifiNetworkAgent(  859): NetworkAgent: NetworkAgent channel lost
D/WifiHS20(  859): hidePasspointNotification off =false
,W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:17.285 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:17.287 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  859): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  859): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/ConnectivityService(  859): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  859):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  859):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/WifiServerServiceExt(  859): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  859): setSupplicantStateSCANNING
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  859): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  859): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): Disconnected - quitting
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/CSLegacyTypeTracker(  859): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  859): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/DhcpStateMachine(  859): StoppedState
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/DhcpStateMachine(  859): StoppedState{ when=-83ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  859): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkPolicy(  859): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  859): MasterInitialState.processMessage what=3
D/ConnectivityService(  859): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  859): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/QCNEJ   ( 1842): |CORE| No family connected
D/ConnectivityService(  859): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  859): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  859): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    (  859): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  859):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  859): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  859): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1842): |CORE| No family connected
I/QCNEJ   ( 1842): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  859): Removing idletimer
I/QCNEJ   ( 1842): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1753): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/Settings(  859): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6300): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6300): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6300): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6300): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6300): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/IndexDatabaseHelper( 6300): Using schema version: 115
,I/IndexDatabaseHelper( 6300): Index is fine
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
I/ActivityManager(  859): Killing 5943:com.android.calendar/u0a13 (adj 15): empty #11
,I/ActivityManager(  859): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6326 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  859): Killing 5805:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  859): failed to open /acct/uid_10013/pid_5943/cgroup.procs: No such file or directory
W/libprocessgroup(  859): failed to open /acct/uid_10069/pid_5805/cgroup.procs: No such file or directory
,I/PCSuite ( 6326): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6326): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6326): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
I/PCSuite ( 6326): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6326): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6326): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
I/PCSuite ( 6326): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6326): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6326): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
I/PCSuite ( 6326): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6326): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6326): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
I/ActivityManager(  859): Killing 5822:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  859): failed to open /acct/uid_10086/pid_5822/cgroup.procs: No such file or directory
,I/wpa_supplicant( 2692): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/Netd    (  283): M: Get netlink event, ifname: wlan0 action: 4
,D/CAR.SERVICE( 6195): mConnectedToCar = false, abort
,E/ActivityThread( 6195): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2022d691 that was originally bound here
E/ActivityThread( 6195): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2022d691 that was originally bound here
E/ActivityThread( 6195): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6195): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6195): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6195): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6195): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6195): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6195): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6195): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6195): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6195): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6195): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6195): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6195): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6195): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6195): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6195): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6195): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6195): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6195): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6195): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6195): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6195): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6195): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@21f196d0 that was originally bound here
E/ActivityThread( 6195): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@21f196d0 that was originally bound here
E/ActivityThread( 6195): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6195): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6195): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6195): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6195): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6195): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6195): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6195): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6195): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6195): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6195): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6195): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6195): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6195): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6195): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6195): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6195): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6195): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6195): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6195): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6195): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  859): Unbind failed: could not find connection for android.os.BinderProxy@23673d01
D/LocSvc_java(  859): onReceive
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:18.396 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/wpa_supplicant( 2692): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  283): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  283): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  283): M: Get netlink event, ifname: wlan0 action: 4
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  859): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  859): setSupplicantStateASSOCIATED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:18.425 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:18.445 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:18.453 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/wpa_supplicant( 2692): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2692): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  283): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  859): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  859): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/WiFiOffLoadBroadcast( 6300): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
,I/WifiServiceExtension(  859): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
I/WifiServerServiceExt(  859): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  859): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  859): setSecurityType  : 2
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:18.52 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:18.524 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  859): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  859): Got NetworkAgent Messenger
D/ConnectivityService(  859): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  859): NetworkAgent connected
D/WifiServiceExtension( 1807): isInternetCheckAvailable return false
E/WifiConfigStore(  859): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
E/WifiConfigStore(  859): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
I/Netd    (  283): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  283): Setting iface cfg
E/WifiStateMachine(  859): Start Dhcp Watchdog 2
D/DhcpStateMachine(  859): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  859): WaitBeforeStartState
D/WifiServerServiceExt(  859): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  859): setSupplicantStateGROUP_HANDSHAKE
,V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  859): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
D/LGWifiP2pService(  859): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@19e16964 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  859): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@19e16964 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  859): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/DhcpStateMachine(  859): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine(  859): Current State is mWaitBeforeStartState.
,D/DhcpStateMachine(  859): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  859): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  283): Setting iface cfg
I/Netd    (  283): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  283): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  859): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  859): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  859): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  859): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  859): setSupplicantStateCOMPLETED
,D/ConnectivityService(  859): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  859): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  859): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  859): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  859): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  859): ignoring duplicate network state non-change
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:18.685 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/WifiServiceExtension( 1807): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  859): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  859): Adding iface wlan0 to network 101
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1807): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine(  859): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  859): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:18.705 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 3
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:18.709 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
,I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiHS20(  859): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:18.72 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
E/ConnectivityService(  859): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  859): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  859): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 3
,D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  283): netlink response contains error (File exists)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  859): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  859): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  859): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  859): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  859): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  859): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  859): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  859): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  859):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  859):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  859):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  859):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  859):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  859): currentScore = 0, newScore = 20
D/ConnectivityService(  859):    accepting network in place of null
D/ConnectivityService(  859): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): EvaluatingS,tate{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1753): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  859): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  859):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): [LWD] Start DNSResolver start to wait
E/ConnectivityService(  859): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  859): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  859): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): [LWD] wait 500ms before dns check
D/ConnectivityService(  859): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  859): [e] list.add(nai) empty : false size: 1
D/Tethering(  859): MasterInitialState.processMessage what=3
D/ConnectivityService(  859): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1842): |CORE| No family connected
I/QCNEJ   ( 1842): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  859): validation of new default Network = false
D/ConnectivityService(  859): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  859): enableDataServiceNotify 
D/DSQN    (  859): start dsqn bin
I/QCNEJ   ( 1842): |CORE| sendDefaultNwMsg: default = 1
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  859): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  859):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  859):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  859): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
I/DSQN    ( 6371): DSQN samuel.seo ver 141203
E/DSQN    ( 6371): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6371): created command queue thread
I/DSQN    ( 6371): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6371): Interface wlan0 netmask 255.255.255.0 0xc0a80186
V/NetworkPolicy(  859): [LG_RESTRICTED] checkMobilePolicy_type()
,V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/PCSuite ( 6326): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6326): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6300): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6300): MCCMNC not supported: null
I/PCSuite ( 6326): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6326): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/DhcpStateMachine(  859): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  859): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  859): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1807): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/dhcpcd  ( 6375): version 5.5.6 starting
,E/dhcpcd  ( 6375): get_duid: Read-only file system
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  859): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/charger_monitor(  483): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/dhcpcd  ( 6375): wlan0: rebinding lease of 192.168.1.134
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
,W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/dhcpcd  ( 6375): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6375): wlan0: leased 192.168.1.134 for 86400 seconds
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): [LWD] DNSResolver start dns
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  283): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  283): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  283): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  283): res_queryN name = xxxxx succeed
,I/System.out(  859): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 6371): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6371): restart monitoring
D/LGDataListener(  283): argv[0]=dsqncommand
D/LGDataListener(  283): argv[1]=wlan0
D/LGDataListener(  283): argv[2]=1
D/LGDataListener(  283): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  859): DSQM DsqnNotification wlan0  1
D/DSQN    (  859): start to monitor internet connection
I/DSQN    ( 6371): dsqn report finish
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 10:50:19 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452509419380], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452509419353]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1807): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  859): Validated
D/ConnectivityService(  859): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  859): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  859):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  859):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  859):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  859): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/WifiDataContinuityService(  859): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  859): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  859):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  859):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  859): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  859): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
I/WifiServerServiceExt(  859): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  859): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  859):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  859): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1753): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  859): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  859): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  859): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  859): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  859): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  859): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  859): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  859): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  859): RunningState
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  859): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,D/ConnectivityService(  859): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  859): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  859): onReceive
D/LocSvc_java(  859): got connectivity action
I/Netd    (  283): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocSvc_java(  859): broadcast - no network connections
D/LocSvc_java(  859): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  859): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  859): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  859): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  859): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  859): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  859): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6419 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ConnectivityService(  859): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  859): identical MTU - not setting
D/Nat464Xlat(  859): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  859): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  859):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  859):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  859): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  859): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  859): enableDataServiceNotify 
D/DSQN    (  859): start dsqn bin
D/LocSvc_java(  859): onReceive
D/LocSvc_java(  859): got connectivity action
D/LocSvc_java(  859): broadcast - no network connections
D/LocSvc_java(  859): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  859): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  859): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  859): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  859): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524295
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:20.421 DNS addrs= 192.168.1.1, 0.0.0.0, 
,D/DSQN    (  859): dsqn is running restart
I/rmt_storage(  280): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  280): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  280): wakelock acquired: 1, error no: 42
I/rmt_storage(  280): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/DSQN    ( 6444): DSQN samuel.seo ver 141203
E/DSQN    ( 6444): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6444): created command queue thread
I/DSQN    ( 6444): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6444): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/GpsLocationProvider(  859): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  859): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  859): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/rmt_storage(  280): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  280): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  280): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  280): 
I/rmt_storage(  280): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/art     (  859): Explicit concurrent mark sweep GC freed 77417(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.574ms total 183.505ms
,I/ActivityManager(  859): Process com.google.android.gms:car (pid 6195) has died
,I/MusicStore( 6419): Database version: 120
,I/ActivityManager(  859): Process com.google.process.gapps (pid 5482) has died
,I/ActivityManager(  859): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6459 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GservicesProvider( 6459): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 6459): GMS http client unavailable, use old client
,I/GoogleHttpClient( 6459): GMS http client unavailable, use old client
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6419): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6419): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6419): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6419): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6419): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6419): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 11:50:21.592 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NotificationManager( 1940): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/WifiInternetCheck(  859): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ActivityThread( 6419): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6419): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@209e9af5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6419): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6419): GMSCore installation verified
D/ConnectivityService(  859): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  859): onReceive
D/LocSvc_java(  859): got connectivity action
D/LocSvc_java(  859): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  859): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  859): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  859): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  859): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/ConfigStore( 6419): Config Database version: 1
,D/GpsLocationProvider(  859): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  859): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{250ce792 type 2 when 105209 com.google.android.gms} when 105209
,I/MediaRouter( 6419): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6419): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6419): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6419): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  859): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6505 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 22.587ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 20.992ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.412ms
,I/GHttpClientFactory( 6419): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6419): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6505): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6505): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6505): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationManager( 6419): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6505): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6505): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6505): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  859): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6532 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/HubEmail( 6505): JNI_OnLoad()
I/HubEmail( 6505): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6505): registerNatives()
I/HubEmail( 6505): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6505): registerNativeMethods()
I/HubEmail( 6505): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6505): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  859): Killing 6089:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/Settings( 6505): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  283): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  283): res_queryN name = xxxxx, class = 1, type = 1
W/libprocessgroup(  859): failed to open /acct/uid_10014/pid_6089/cgroup.procs: No such file or directory
D/libc-netbsd(  283): res_queryN name = xxxxx succeed
,I/System.out(  859): propertyValue:false
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  283): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  283): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  283): res_queryN name = xxxxx succeed
I/System.out(  859): propertyValue:false
I/DSQN    ( 6444): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6444): restart monitoring
I/DSQN    ( 6444): dsqn report finish
,D/LGDataListener(  283): argv[0]=dsqncommand
D/LGDataListener(  283): argv[1]=wlan0
D/LGDataListener(  283): argv[2]=1
D/LGDataListener(  283): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  859): DSQM DsqnNotification wlan0  1
D/DSQN    (  859): start to monitor internet connection
I/ActivityManager(  859): Process com.android.vending (pid 6022) has died
D/LGDMClient( 6532): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6532): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6532): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/WifiInternetCheck(  859): isHttpConnectionAvailable - We got a valid response : 204
W/ContextImpl( 6532): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6532): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6532): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 6532): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6532): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  859): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6565 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6532): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6532): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6532): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6532): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6532): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6532): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 6565): onCreate
,W/AppUp4:DB( 6565):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6565):  setFingerPrint start
I/AppUp4:DB( 6565):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6565):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6565):  SDK version = 0
I/AppUp4:DB( 6565):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6565): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6565): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6565): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6565): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6565): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6565): onReceive
I/AppUp4:CustModeStarterReceiver( 6565): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6565): Context : android.app.ReceiverRestrictedContext@4666909
D/AppUp4:CustFacade( 6565): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6565): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6565): begin check event
I/AppUp4:CustModeStarterReceiver( 6565): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6565): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6565): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6565): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6565): handleAsyncCustNotification do not startCustService
I/ActivityManager(  859): Killing 5644:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  859): failed to open /acct/uid_10061/pid_5644/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3180): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3180): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3180): networkInfo.isConnected() = false
,I/ActivityManager(  859): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6590 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6590): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6590): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6590): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  859): Killing 6300:com.android.settings/1000 (adj 15): empty #11
,D/PhoneMonitor( 6590): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6590): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6590): [parse] Load xml
V/TelephonyAutoProfiling( 6590): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6590): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6590): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  859): failed to open /acct/uid_1000/pid_6300/cgroup.procs: No such file or directory
,I/CheckinService( 4217): Checkin interval check for package: unspecified last checkin: 1452509396475 min interval config: 0 actual interval: 27249
,V/DownloadManager( 3252): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3252): DownloadService onCreate
,I/ActivityManager(  859): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6612 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/NotificationManager( 3252): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3252): in removeSpuriousFiles
V/DownloadManager( 3252): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3252): created cursor android.database.sqlite.SQLiteCursor@18bcd559 on behalf of 3252
,I/DownloadManager( 3252): in trimDatabase
V/DownloadManager( 3252): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3252): created cursor android.database.sqlite.SQLiteCursor@2d3e251e on behalf of 3252
I/CheckinService( 4217): Checking schedule, now: 1452509423855 next: 1452509426427
I/CheckinService( 4217): active receiver: disabled
,V/DownloadManager( 3252): DownloadService onStartCommand
V/DownloadManager( 3252): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3252): created cursor android.database.sqlite.SQLiteCursor@26dc6e15 on behalf of 3252
,I/ActivityManager(  859): Killing 5712:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5096): android.os.DeadObjectException
,W/System.err( 5096): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5096): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5096): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,W/System.err( 5096): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5096): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5096): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5096): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5096): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5096): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5096): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5096): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5096): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5096): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5096): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5096): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5096): android.os.DeadObjectException
W/System.err( 5096): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5096): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5096): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5096): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5096): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5096): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5096): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5096): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5096): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5096): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5096): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5096): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5096): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5096): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5096): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  859): failed to open /acct/uid_10089/pid_5712/cgroup.procs: No such file or directory
W/ActivityManager(  859): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/WeatherAncestor( 2572): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:50:24
I/ActivityManager(  859): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6646 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DownloadManager( 3252): DownloadService onDestroy
D/UpdateThreadPoolManager( 2572): 2 : This is isUpdating : false
D/WeatherAncestor( 2572): connectivity changed - connection : true
D/Weather_cast( 2572): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2572): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:50:24
D/WeatherService( 2572): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  859): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6666 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  859): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2572): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2572): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2572): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6646): Quickset Services start...
,I/UEI.SmartControl( 6646): Manufacture = LGE
D/UEI.SmartControl( 6646): File observer start...
E/UEI.SmartControl( 6646): IR Port is disabled: false
D/UEI.SmartControl( 6646): Starting file observer...
D/UEI.SmartControl( 6646): Extracting JNI libs...
D/UEI.SmartControl( 6646): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 6666): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6646): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6646): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6646): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6646): --- Selecting new region: 2
I/UEI.SmartControl( 6646): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6646): Platform has CIR...
D/UEI.SmartControl( 6646): NO CIR support, need to check package...
I/UEI.SmartControl( 6646): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6646): QS Service created
E/UEI.SmartControl( 6646): QS start get config
,D/UEI.SmartControl( 6646): Loading JNI Libs...
D/UEI.SmartControl( 6646):  configuring local db...
,I/Babel_SMS( 6666): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6666): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6666): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6666): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6666): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6666): MmsConfig.loadFromResources
E/Babel_SMS( 6666): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6666): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6666): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6666): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6666): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6666): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6666): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6666): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6666): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6666): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6666): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6666): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6666): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6666): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6666): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6666): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6666): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6666): found sensor: Motion Accel, handle=46
,I/art     ( 6666): CheckpointMarkThreadRoots callback created = 0xb042d880
D/UEI.SmartControl( 6646):  ---- Has DB8: true
D/UEI.SmartControl( 6646): QS start statue = true Error code = 0
D/UEI.SmartControl( 6646): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6646): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6646): IRRCDataComm has AudioManager!!!!.
,W/Settings( 6666): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6666): startup - clean
I/art     ( 6666): CheckpointMarkThreadRoots callback created = 0xb042d860
,W/irrc_jni( 6646): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6646): IrrcClient ++ 
D/irrcClient( 6646): getIrrcService ++ 
D/irrcClient( 6646): getIrrcService -- 
D/irrcClient( 6646): IrrcClient -- 
W/irrc_jni( 6646): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6646): Services init done
,I/UEI.SmartControl( 6646): Device manager: loading config....
D/UEI.SmartControl( 6646): Config is loaded...
,I/Babel   ( 6666): deleted: false for 0
,D/UEI.SmartControl( 6646):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6646): Notify AllClients services are ready: 0
,I/ActivityManager(  859): Process com.google.android.music:main (pid 6419) has died
,D/UEI.SmartControl( 6646): QS Service init finished
D/UEI.SmartControl( 6646): QS Service version name: 0.1.73
D/UEI.SmartControl( 6646): QS Service version code: 1073
D/UEI.SmartControl( 6646): Service requested: Control
D/UEI.SmartControl( 6646): -----IControl: 11
D/UEI.SmartControl( 6646): Internal service binding...
,D/UEI.SmartControl( 6646): Caller: com.lge.qremote
D/UEI.SmartControl( 6646): ------------ IControl registerCallback...
I/UEI.SmartControl( 6646): Registering callback...
D/UEI.SmartControl( 6646): -----IControl: 19
D/UEI.SmartControl( 6646): Caller: com.lge.qremote
I/UEI.SmartControl( 6646): Registering Services Ready callback...
I/UEI.SmartControl( 6646): Notify client services are ready...
D/UEI.SmartControl( 6646): -----IControl: 8
D/UEI.SmartControl( 6646): Caller: com.lge.qremote
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,W/AudioCapabilities( 6666): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6666): Unsupported mime audio/adpcm
,I/ActivityManager(  859): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6715 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 6666): Unsupported mime audio/g726
,W/AudioCapabilities( 6666): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6666): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6666): Unsupported mime video/mjpg
W/VideoCapabilities( 6666): Unsupported mime video/theora
,W/AudioCapabilities( 6666): Unsupported mime audio/evrc
,W/AudioCapabilities( 6666): Unsupported mime audio/qcelp
W/VideoCapabilities( 6666): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6666): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6666): Unsupported mime audio/qcelp
W/AudioCapabilities( 6666): Unsupported mime audio/evrc
,W/VideoCapabilities( 6666): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6666): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6666): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6666): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6666): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6666): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6666): onServiceConnected
W/Babel   ( 6666): Attempted to change video mute state without an active call.
I/NotificationManager( 6666): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6666): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6666): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6666): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6666): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  283): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  283): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  283): res_queryN name = xxxxx succeed
,I/System.out( 6666): propertyValue:false
I/Babel   ( 6666): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  859): Process com.lge.email (pid 6505) has died
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6715): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6715): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6715): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6715): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6715): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6715):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6715):   adb logcat -s GAv4
W/GAv4    ( 6715): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6715): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6715): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6715): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6715): Time to load native libraries: 2 ms (timestamps 9404-9406)
,I/LibraryLoader( 6715): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6715): Binding Chromium to main looper Looper (main, tid 1) {e817f82}
I/LibraryLoader( 6715): Expected native library version number "",actual native library version number ""
I/chromium( 6715): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6715): Initializing chromium process, singleProcess=true
W/art     ( 6715): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6715): ApplicationContext is null in ApplicationStatus
,W/chromium( 6715): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6715): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6715): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6715): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6715): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6715): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6715): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6715): Remote Branch: 
I/Adreno-EGL( 6715): Local Patches: 
I/Adreno-EGL( 6715): Reconstruct Branch: 
V/AudioPolicyService(  289): registerClient() client 0xb57ea600, uid 10079
,W/AudioManagerAndroid( 6715): Requires BLUETOOTH permission
I/NSApplication( 6715): Starting up...
I/ActivityManager(  859): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6778 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 6326:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  859): failed to open /acct/uid_1000/pid_6326/cgroup.procs: No such file or directory
,I/ActivityManager(  859): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6797 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 5096:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  859): failed to open /acct/uid_10106/pid_5096/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     (  859): Explicit concurrent mark sweep GC freed 26326(1412KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.259ms total 150.926ms
,W/ResourcesManager( 6797): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/AlarmManager(  859): RTC_WAKEUP set : Alarm{d22236b type 0 when 1452509426427 com.google.android.gms} when 1452509426427
,V/AlarmManager(  859): RTC_WAKEUP set : Alarm{3fe0fb61 type 0 when 1452509427031 com.google.android.googlequicksearchbox} when 1452509427031
I/ActivityManager(  859): Killing 6532:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  859): failed to open /acct/uid_1000/pid_6532/cgroup.procs: No such file or directory
,I/ActivityManager(  859): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6826 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6826): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6826): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6826): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6826): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6826): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6826): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6826): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6826): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6826): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@209e9af5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6826): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6826): GMSCore installation verified
I/ConfigStore( 6826): Config Database version: 1
,I/MediaRouter( 6826): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6826): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6826): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6826): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  859): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6861 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 25.934ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 23.798ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 24.328ms
I/GHttpClientFactory( 6826): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6826): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  859): Killing 6565:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6861): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6861): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6861): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  859): failed to open /acct/uid_10011/pid_6565/cgroup.procs: No such file or directory
,I/NotificationManager( 6826): com.google.android.music: cancel(1061) by com.google.android.music
I/ActivityManager(  859): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6888 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  859): RTC_WAKEUP set : Alarm{140d6e04 type 0 when 1452509428615 com.android.vending} when 1452509428615
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/LGEmail ( 6861): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6861): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/Finsky  ( 6888): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/eas_req ( 6861): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  859): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6920 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  859): Process com.uei.lg.quicksetsdk.lite (pid 6646) has died
,I/HubEmail( 6861): JNI_OnLoad()
I/HubEmail( 6861): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6861): registerNatives()
I/HubEmail( 6861): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6861): registerNativeMethods()
I/HubEmail( 6861): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6861): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,D/Finsky  ( 6888): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 6888): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6888): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6888): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  859): Process com.google.android.setupwizard (pid 6590) has died
,W/Settings( 6861): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3252): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 6920): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3252): created cursor android.database.sqlite.SQLiteCursor@31c7df1b on behalf of 6888
,D/LGDMClient( 6920): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6920): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/Finsky  ( 6888): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6888): [1] Libraries$2.run: Finished loading 1 libraries.
W/ContextImpl( 6920): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/Ads     ( 6888): Skipping gmscore version check
D/Finsky  ( 6888): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/LGDMClient( 6920): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6920): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6920): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6920): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  859): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6974 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 6920): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6920): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6920): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6920): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6920): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6920): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,D/Finsky  ( 6888): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/AppUp4:AppBoxCP( 6974): onCreate
,W/AppUp4:DB( 6974):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6974):  setFingerPrint start
I/AppUp4:DB( 6974):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6974):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6974):  SDK version = 0
I/AppUp4:DB( 6974):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6974): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6974): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6974): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6974): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6974): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6974): onReceive
I/AppUp4:CustModeStarterReceiver( 6974): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6974): Context : android.app.ReceiverRestrictedContext@4666909
,D/AppUp4:CustFacade( 6974): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6974): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6974): begin check event
I/AppUp4:CustModeStarterReceiver( 6974): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6974): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6974): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6974): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6974): handleAsyncCustNotification do not startCustService
I/ActivityManager(  859): Killing 6612:com.lge.drmservice/u0a51 (adj 15): empty #11
D/Finsky  ( 6888): [850] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6888): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
W/libprocessgroup(  859): failed to open /acct/uid_10051/pid_6612/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3180): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3180): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3180): networkInfo.isConnected() = false
I/ActivityManager(  859): Killing 6666:com.google.android.talk/u0a61 (adj 15): empty #11
I/ActivityManager(  859): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6997 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
W/libprocessgroup(  859): failed to open /acct/uid_10061/pid_6666/cgroup.procs: No such file or directory
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,D/PhoneMonitor( 6997): Register our PhoneStateListener
,I/jxcore-log( 6142): Test app app.js loaded
I/jxcore-log( 6142): 
,D/MobileConnectivityChangeReceiver( 6997): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6997): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  859): Killing 6715:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,D/PhoneMonitor( 6997): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6997): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6997): [parse] Load xml
,V/TelephonyAutoProfiling( 6997): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6997): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6997): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/chromium( 6142): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup(  859): failed to open /acct/uid_10079/pid_6715/cgroup.procs: No such file or directory
,V/DownloadManager( 3252): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3252): DownloadService onCreate
,I/DownloadManager( 3252): in removeSpuriousFiles
V/DownloadManager( 3252): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3252): created cursor android.database.sqlite.SQLiteCursor@1f668b8 on behalf of 3252
I/NotificationManager( 3252): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3252): in trimDatabase
V/DownloadManager( 3252): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3252): created cursor android.database.sqlite.SQLiteCursor@2022d691 on behalf of 3252
,I/ActivityManager(  859): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7019 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3252): DownloadService onStartCommand
V/DownloadManager( 3252): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3252): created cursor android.database.sqlite.SQLiteCursor@3a055864 on behalf of 3252
,I/CheckinService( 4217): Checkin interval check for package: unspecified last checkin: 1452509396475 min interval config: 0 actual interval: 34086
I/CheckinService( 4217): Checking schedule, now: 1452509430571 next: 1452509426427
,I/CheckinService( 4217): active receiver: enabled
,I/CheckinService( 4217): Preparing to send checkin request
I/EventLogService( 4217): Accumulating logs since 1452509388377
,V/DownloadManager( 3252): DownloadService onDestroy
,I/CheckinRequestBuilder( 4217): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4217): Failed to find provider info for com.google.android.wearable.settings
D/WeatherAncestor( 2572): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:50:30
D/UpdateThreadPoolManager( 2572): 2 : This is isUpdating : false
,D/WeatherAncestor( 2572): connectivity changed - connection : true
D/Weather_cast( 2572): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2572): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:50:30
D/WeatherService( 2572): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  859): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7042 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  859): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2572): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2572): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
,D/WeatherService( 2572): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ResourcesManager( 7042): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  859): Explicit concurrent mark sweep GC freed 19412(925KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.387ms total 150.403ms
,I/ActivityManager(  859): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7065 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     ( 7042): CheckpointMarkThreadRoots callback created = 0xb042d440
,I/Babel_SMS( 7042): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7042): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7042): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7042): MmsConfig.loadFromDatabase
I/art     ( 7042): CheckpointMarkThreadRoots callback created = 0xb042d420
,E/Babel_SMS( 7042): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7042): MmsConfig.loadFromResources
E/Babel_SMS( 7042): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7042): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/ResourcesManager( 7065): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SensorManager( 7042): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7042): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7042): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7042): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7042): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7042): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7042): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7042): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7042): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7042): found sensor: LGE Significant Motion Detector Sensor, handle=47
,D/SensorManager( 7042): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7042): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7042): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7042): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7042): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7042): found sensor: Motion Accel, handle=46
I/MultiDex( 7065): VM with version 2.1.0 has multidex support
I/MultiDex( 7065): install
I/MultiDex( 7065): VM has multidex support, MultiDex support library is disabled.
,W/Settings( 7042): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7042): startup - clean
I/Babel   ( 7042): deleted: false for 0
,V/JNIHelp ( 7065): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 114799991314; DSPS: 3859668; Offset : -2998727967
,W/ActivityThread( 7065): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  859): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7099 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/System  ( 7065): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ce1fdd2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7065): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7065): com.google.android.gms: cancel(10436) by com.google.android.gms
,W/AudioCapabilities( 7042): Unsupported mime audio/x-lg-flac
I/NotificationManager( 7065): com.google.android.gms: cancel(39789) by com.google.android.gms
W/AudioCapabilities( 7042): Unsupported mime audio/adpcm
W/AudioCapabilities( 7042): Unsupported mime audio/g726
W/AudioCapabilities( 7042): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7042): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7042): Unsupported mime video/mjpg
,W/VideoCapabilities( 7042): Unsupported mime video/theora
W/AudioCapabilities( 7042): Unsupported mime audio/evrc
,W/AudioCapabilities( 7042): Unsupported mime audio/qcelp
W/VideoCapabilities( 7042): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7042): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7042): Unsupported mime audio/qcelp
W/AudioCapabilities( 7042): Unsupported mime audio/evrc
W/VideoCapabilities( 7042): Unsupported mime video/mp4v-esdp
,I/art     ( 7065): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7065): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/VideoCapabilities( 7042): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7042): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7042): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7042): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7042): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7042): onServiceConnected
W/Babel   ( 7042): Attempted to change video mute state without an active call.
,I/NotificationManager( 7042): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7042): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7042): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7042): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7042): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  283): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  283): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  283): res_queryN name = xxxxx succeed
,I/System.out( 7042): propertyValue:false
I/Babel   ( 7042): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  859): Killing 6778:com.android.chrome/u0a48 (adj 15): empty #11
D/NativeLibraryUtils( 7065): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  859): failed to open /acct/uid_10048/pid_6778/cgroup.procs: No such file or directory
,D/WVCdm   (  289): Instantiating CDM.
,I/WVCdm   (  289): CdmEngine::OpenSession
I/WVCdm   (  289): Level3 Library Dec 11 2014 16:13:16
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7099): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7099): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/WVCdm   (  289): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  289): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  289): L1 library not specified. Falling Back to L3
I/GAv4    ( 7099): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7099):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7099):   adb logcat -s GAv4
,W/GAv4    ( 7099): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7099): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7099): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/WVCdm   (  289): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  289): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  289): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  289): CdmEngine::GenerateKeyRequest
D/WVCdm   (  289): PrepareKeyRequest: nonce=3589947151
,W/GAv4    ( 7099): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7099): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7099): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     ( 7065): CheckpointMarkThreadRoots callback created = 0xb04d4eb0
,I/ActivityManager(  859): Process com.google.android.music:main (pid 6826) has died
,I/art     ( 7065): CheckpointMarkThreadRoots callback created = 0xb04d4ea0
I/LibraryLoader( 7099): Time to load native libraries: 2 ms (timestamps 5823-5825)
,I/LibraryLoader( 7099): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7099): Binding Chromium to main looper Looper (main, tid 1) {e817f82}
I/LibraryLoader( 7099): Expected native library version number "",actual native library version number ""
I/chromium( 7099): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7099): Initializing chromium process, singleProcess=true
,W/art     ( 7099): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7099): ApplicationContext is null in ApplicationStatus
I/dex2oat ( 7143): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/chromium( 7099): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7099): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7099): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7099): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7099): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7099): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7099): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7099): Remote Branch: 
I/Adreno-EGL( 7099): Local Patches: 
I/Adreno-EGL( 7099): Reconstruct Branch: 
V/AudioPolicyService(  289): registerClient() client 0xb57ea680, uid 10079
,W/AudioManagerAndroid( 7099): Requires BLUETOOTH permission
I/dex2oat ( 7143): dex2oat took 103.201ms (threads: 4)
I/NSApplication( 7099): Starting up...
I/Adreno-EGL( 7065): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7065): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7065): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7065): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7065): Remote Branch: 
I/Adreno-EGL( 7065): Local Patches: 
I/Adreno-EGL( 7065): Reconstruct Branch: 
,I/ActivityManager(  859): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7167 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Adreno-EGL( 7065): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7065): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7065): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7065): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7065): Remote Branch: 
I/Adreno-EGL( 7065): Local Patches: 
I/Adreno-EGL( 7065): Reconstruct Branch: 
,I/ActivityManager(  859): Process com.android.vending (pid 6888) has died
,I/art     ( 6797): CheckpointMarkThreadRoots callback created = 0xb042de00
,I/art     ( 6797): CheckpointMarkThreadRoots callback created = 0xb042ddf0
,I/ActivityManager(  859): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7187 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7187): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7187): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7187): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7187): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  859): Process com.lge.email (pid 6861) has died
,I/WVCdm   (  289): CdmEngine::OpenSession
,W/ResourcesManager( 7187): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7187): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7187): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7187): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7187): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@209e9af5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7187): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7187): GMSCore installation verified
I/ConfigStore( 7187): Config Database version: 1
,I/MediaRouter( 7187): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7187): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7187): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7187): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  859): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7220 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.556ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.570ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 359us total 21.971ms
,I/MusicWidget( 2544): mDelayedStopHandler : unbind
,I/MusicBrowser( 2592): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2592): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2592): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/GHttpClientFactory( 7187): Using our fixed implementation of GMSCore's GoogleHttpClient
D/MusicBrowser( 2592): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2592): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2592): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
W/ResourcesManager( 7220): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7220): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7220): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/MusicBrowser( 2592): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/GoogleURLConnFactory( 7187): Using platform SSLCertificateSocketFactory
I/MusicBrowser( 2592): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  859):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3e3befbecom.lge.music.MediaPlaybackService$6@2d85281f
D/MusicBrowser( 2592): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2592): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2592): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2592): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2592): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@3838cc5
I/MusicBrowser( 2592): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2592): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2592): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2592): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2592): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2592): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2592): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2592): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2592): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2592): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2592): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2592): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2592): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2592): reset
I/NotificationManager( 7187): com.google.android.music: cancel(1061) by com.google.android.music
,V/MediaPlayer[Native]( 2592): setListener
V/MediaPlayer[Native]( 2592): disconnect
V/MediaPlayer[Native]( 2592): destructor
V/AudioFlinger(  289): releasing 19 from 2592 for -1
,V/AudioFlinger(  289):  decremented refcount to 0
V/AudioFlinger(  289): purging stale effects
V/MediaPlayer[Native]( 2592): disconnect
D/MusicBrowser( 2592): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2592): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2592): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2592): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2592): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2592): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2592): [SmartShareManagerClient] unregisterListener: 451262316
W/SmartShareClient( 2592): [SmartShareManagerClient] unregisterListener invalid listener: 451262316
I/SmartShareClient( 2592): [SmartShareManagerClient] terminate service: 2592/MediaPlaybackService/770629331
E/HomeCloudIF( 2592): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2592): [SmartShareManagerClient] unbindService context:android.app.Application@3b3a3135
I/LGEmail ( 7220): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,V/CloudHub( 2592): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2592): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2592): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2592): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2592): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
D/LGEmail ( 7220): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/ActivityManager(  859): Killing 6920:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/CloudHub( 2592): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29986
,I/WVCdm   (  289): CdmEngine::CloseSession
,W/libprocessgroup(  859): failed to open /acct/uid_1000/pid_6920/cgroup.procs: No such file or directory
,I/WVCdm   (  289): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  289): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  289): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  289): CdmEngine::GenerateKeyRequest
I/ActivityManager(  859): Process com.google.android.talk (pid 7042) has died
D/WVCdm   (  289): PrepareKeyRequest: nonce=2616299601
,D/eas_req ( 7220): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  859): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7253 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7220): JNI_OnLoad()
I/HubEmail( 7220): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7220): registerNatives()
I/HubEmail( 7220): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 7220): registerNativeMethods()
I/HubEmail( 7220): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7220): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7220): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 7253): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7253): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7253): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7253): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 6974): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6974): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6974): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6974): [onReceive] request level :IDLE....
,D/LGDMClient( 7253): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7253): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/AppUp4:CustModeStarterReceiver( 6974): onReceive
I/AppUp4:CustModeStarterReceiver( 6974): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6974): Context : android.app.ReceiverRestrictedContext@4666909
D/AppUp4:CustFacade( 6974): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6974): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6974): begin check event
I/AppUp4:CustModeStarterReceiver( 6974): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/LgeMiscReceiver( 3180): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3180): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3180): networkInfo.isConnected() = true
,D/LGDMClient( 7253): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/PhoneState( 3180): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 6997): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6997): onReceive CONNECTIVITY_CHANGE networkType=1
I/LGDMClient( 7253): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3252): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3252): DownloadService onCreate
I/DownloadManager( 3252): in removeSpuriousFiles
V/DownloadManager( 3252): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/WeatherAncestor( 2572): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:50:34
V/DownloadManager( 3252): created cursor android.database.sqlite.SQLiteCursor@e817f82 on behalf of 3252
,D/UpdateThreadPoolManager( 2572): 2 : This is isUpdating : false
D/WeatherAncestor( 2572): connectivity changed - connection : true
D/Weather_cast( 2572): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2572): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:50:34
I/DownloadManager( 3252): in trimDatabase
V/DownloadManager( 3252): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/NotificationManager( 3252): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/WeatherService( 2572): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3252): created cursor android.database.sqlite.SQLiteCursor@2891693 on behalf of 3252
I/ActivityManager(  859): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7286 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  859): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2572): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3252): DownloadService onStartCommand
W/ContextImpl( 7253): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3252): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3252): created cursor android.database.sqlite.SQLiteCursor@244c11ce on behalf of 3252
E/LGDMClient( 7253): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7253): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7253): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/WeatherService( 2572): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2572): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/LGDMClient( 7253): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7253): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  859): Killing 7099:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  859): failed to open /acct/uid_10079/pid_7099/cgroup.procs: No such file or directory
V/DownloadManager( 3252): DownloadService onDestroy
W/ResourcesManager( 7286): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7286): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7286): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7286): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7286): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7286): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7286): MmsConfig.loadFromResources
E/Babel_SMS( 7286): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7286): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7286): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7286): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7286): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7286): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7286): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7286): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7286): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7286): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7286): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7286): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7286): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7286): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7286): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7286): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7286): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7286): found sensor: Motion Accel, handle=46
,W/Settings( 7286): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7286): startup - clean
I/Babel   ( 7286): deleted: false for 0
,I/art     ( 7286): CheckpointMarkThreadRoots callback created = 0xaaf40be0
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
I/ActivityManager(  859): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7320 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7286): CheckpointMarkThreadRoots callback created = 0xaaf40bc0
W/AudioCapabilities( 7286): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7286): Unsupported mime audio/adpcm
W/AudioCapabilities( 7286): Unsupported mime audio/g726
W/AudioCapabilities( 7286): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7286): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7286): Unsupported mime video/mjpg
W/VideoCapabilities( 7286): Unsupported mime video/theora
,W/AudioCapabilities( 7286): Unsupported mime audio/evrc
W/AudioCapabilities( 7286): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7286): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7286): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7286): Unsupported mime audio/qcelp
W/AudioCapabilities( 7286): Unsupported mime audio/evrc
,W/VideoCapabilities( 7286): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7286): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7286): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7286): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7286): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7286): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7286): onServiceConnected
W/Babel   ( 7286): Attempted to change video mute state without an active call.
,D/libc-netbsd( 7286): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7286): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7286): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7286): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  283): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  283): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  283): res_queryN name = xxxxx succeed
I/System.out( 7286): propertyValue:false
I/NotificationManager( 7286): com.google.android.talk: cancel(10436) by com.google.android.talk
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7320): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/Babel   ( 7286): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  859): Killing 7167:com.android.chrome/u0a48 (adj 15): empty #11
I/GAv4    ( 7320): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7320):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7320):   adb logcat -s GAv4
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7320): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7320): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7320): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/libprocessgroup(  859): failed to open /acct/uid_10048/pid_7167/cgroup.procs: No such file or directory
,W/GAv4    ( 7320): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7320): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7320): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7320): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     (  859): Explicit concurrent mark sweep GC freed 17705(841KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.565ms total 161.344ms
I/art     (  859): WaitForGcToComplete blocked for 54.860ms for cause HeapTrim
,I/LibraryLoader( 7320): Time to load native libraries: 2 ms (timestamps 9508-9510)
I/LibraryLoader( 7320): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7320): Binding Chromium to main looper Looper (main, tid 1) {e817f82}
I/LibraryLoader( 7320): Expected native library version number "",actual native library version number ""
I/chromium( 7320): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/WVCdm   (  289): CdmEngine::CloseSession
I/WVCdm   (  289): L3 Terminate.
,I/BrowserStartupController( 7320): Initializing chromium process, singleProcess=true
W/art     ( 7320): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7320): ApplicationContext is null in ApplicationStatus
I/Adreno-EGL( 7065): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7065): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7065): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7065): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7065): Remote Branch: 
I/Adreno-EGL( 7065): Local Patches: 
I/Adreno-EGL( 7065): Reconstruct Branch: 
W/chromium( 7320): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7320): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7320): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7320): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7320): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7320): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7320): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7320): Remote Branch: 
I/Adreno-EGL( 7320): Local Patches: 
I/Adreno-EGL( 7320): Reconstruct Branch: 
V/AudioPolicyService(  289): registerClient() client 0xb57ea600, uid 10079
,W/AudioManagerAndroid( 7320): Requires BLUETOOTH permission
I/NSApplication( 7320): Starting up...
,I/CheckinRequestBuilder( 4217): Classify the device as Phone.
,I/ActivityManager(  859): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7389 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 6797:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  859): failed to open /acct/uid_10086/pid_6797/cgroup.procs: No such file or directory
,D/libc-netbsd( 4217): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4217): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4217): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4217): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  283): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  283): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  283): res_queryN name = xxxxx succeed
I/System.out( 4217): propertyValue:false
,D/libc-netbsd( 4217): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4217): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  859): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7410 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  859): Killing 7187:com.google.android.music:main/u0a81 (adj 15): empty #11
D/libc-netbsd( 4217): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4217): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4217): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4217): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4217): Sending checkin request (9743 bytes)
,W/libprocessgroup(  859): failed to open /acct/uid_10081/pid_7187/cgroup.procs: No such file or directory
W/ResourcesManager( 7410): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 4217): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4217): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager(  859): Killing 2592:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  289): 2592 died, releasing its sessions
V/AudioFlinger(  289):  pid 1753 @ 0
,V/AudioFlinger(  289):  pid 3180 @ 1
V/AudioFlinger(  289):  pid 3180 @ 2
W/libprocessgroup(  859): failed to open /acct/uid_10028/pid_2592/cgroup.procs: No such file or directory
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  283): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  283): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  283): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  283): res_queryN name = xxxxx succeed
,I/System.out( 1735): propertyValue:false
I/art     ( 6459): Explicit concurrent mark sweep GC freed 2189(95KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 452us total 52.106ms
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  859): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7439 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 7439): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4217): Classify the device as Phone.
,I/CheckinTask( 4217): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4217): Checking schedule, now: 1452509437321 next: 1453036686315
I/CheckinService( 4217): active receiver: disabled
D/BluetoothManagerService(  859): Message: 20
D/BluetoothManagerService(  859): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16d53428:true
,D/CheckinService( 4217): Recording last checkin time for package unspecified as 1452509437348
,D/BluetoothAdapterService(32769852)( 2007): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@15aa5e72
D/BluetoothAdapterService(32769852)( 2007): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@15aa5e72
I/ActivityManager(  859): Killing 6974:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  859): Killing 7220:com.lge.email/u0a21 (adj 15): empty #12
,W/libprocessgroup(  859): failed to open /acct/uid_10011/pid_6974/cgroup.procs: No such file or directory
,I/ActivityManager(  859): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7472 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  859): failed to open /acct/uid_10021/pid_7220/cgroup.procs: No such file or directory
V/LGMDMManager( 7439): Create singleton instance
,D/UEI.SmartControl( 7472): Quickset Services start...
,I/UEI.SmartControl( 7472): Manufacture = LGE
D/UEI.SmartControl( 7472): File observer start...
E/UEI.SmartControl( 7472): IR Port is disabled: false
D/UEI.SmartControl( 7472): Starting file observer...
D/UEI.SmartControl( 7472): Extracting JNI libs...
D/UEI.SmartControl( 7472): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7439): getMode name:com.lge.qremote
,I/CheckinService( 4217): Checkin interval check for package: unspecified last checkin: 1452509437348 min interval config: 0 actual interval: 269
,I/CheckinService( 4217): Checking schedule, now: 1452509437623 next: 1453036686315
I/CheckinService( 4217): active receiver: disabled
D/WearableService( 1735): callingUid 10006, callindPid: 1735
,D/LocationInitializer( 4217): Restart initialization of location
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/ContextImpl( 3629): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,E/MDM     ( 1735): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1735): No location to return for getLastLocation()
,W/FusedLocationProvider( 1735): location=null
V/SetupWizard( 6997): Connected to Gservices successfully
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7472): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7472): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7472): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/AudioManager( 7439): getMode name:com.lge.qremote
,I/UEI.SmartControl( 7472): --- Selecting new region: 2
I/UEI.SmartControl( 7472): -- Running on KitKat(19) and above! JNI will be used.
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/UEI.SmartControl( 7472): Platform has CIR...
D/UEI.SmartControl( 7472): NO CIR support, need to check package...
I/UEI.SmartControl( 7472): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7472): QS Service created
,E/UEI.SmartControl( 7472): QS start get config
,D/UEI.SmartControl( 7472): Loading JNI Libs...
,D/UEI.SmartControl( 7472):  configuring local db...
,D/UEI.SmartControl( 7472):  ---- Has DB8: true
,D/UEI.SmartControl( 7472): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7472): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7472): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7472): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7472): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 7472): IrrcClient ++ 
D/irrcClient( 7472): getIrrcService ++ 
D/irrcClient( 7472): getIrrcService -- 
D/irrcClient( 7472): IrrcClient -- 
W/irrc_jni( 7472): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7472): Services init done
I/UEI.SmartControl( 7472): Device manager: loading config....
D/UEI.SmartControl( 7472): QS Service init finished
D/UEI.SmartControl( 7472): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7472): QS Service version code: 1073
D/UEI.SmartControl( 7472): Service requested: Control
D/UEI.SmartControl( 7472): Config is loaded...
D/UEI.SmartControl( 7472):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7472): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7472): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7472): Internal service binding...
D/UEI.SmartControl( 7472): -----IControl: 11
D/UEI.SmartControl( 7472): Caller: com.lge.qremote
D/UEI.SmartControl( 7472): ------------ IControl registerCallback...
I/UEI.SmartControl( 7472): Registering callback...,
D/UEI.SmartControl( 7472): -----IControl: 19
D/UEI.SmartControl( 7472): Caller: com.lge.qremote
,I/UEI.SmartControl( 7472): Registering Services Ready callback...
I/UEI.SmartControl( 7472): Notify client services are ready...
D/UEI.SmartControl( 7472): -----IControl: 8
D/UEI.SmartControl( 7472): Caller: com.lge.qremote
I/AudioManager( 7439): getMode name:com.lge.qremote
,I/AudioManager( 7439): getMode name:com.lge.qremote
,I/AudioManager( 7439): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  859): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  859): Handling package changes for user 0
,I/ActivityManager(  859): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7544 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationManager( 7286): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7286): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7286): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7286): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 7544): onCreate
W/AppUp4:DB( 7544):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7544):  setFingerPrint start
I/AppUp4:DB( 7544):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7544):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 7544):  SDK version = 0
I/AppUp4:DB( 7544):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7544): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7544): onReceive
I/AppUp4:CustModeStarterReceiver( 7544): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7544): Context : android.app.ReceiverRestrictedContext@12bc40c2
,D/AppUp4:CustFacade( 7544): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7544): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7544): begin check event
I/AppUp4:CustModeStarterReceiver( 7544): Event For Nothing, skip.
W/System  ( 7286): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7286): Installed default security provider GmsCore_OpenSSL
,I/NotificationService(  859): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  859): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  859): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  859): Process com.google.android.apps.magazines (pid 7320) has died
,W/ResourcesManager(  859): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  859): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7566 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/BackupManagerService(  859): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
,V/BackupManagerService(  859): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  859): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@5548363
,W/ResourcesManager( 7566): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7566): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7566): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType(  859): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  859): applying state to connected service
,I/AppConfig( 7566): Total System Memory = 906309632
,I/GalleryUtils( 7566): Application Heap = 96 MB
I/AppConfig( 7566): App Tier : NOT_DEF
D/SystemHelper( 7566): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  859): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7592 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  859): Killing 7019:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  859): failed to open /acct/uid_10051/pid_7019/cgroup.procs: No such file or directory
,W/ResourcesManager( 7592): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7592): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7592): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7592): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7592): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7592): BUILD Country: EU
I/SystemConfig( 7592): BUILD Operator: OPEN
,I/ActivityManager(  859): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7614 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  859): Killing 7253:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 452us total 25.720ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 22.030ms
,W/libprocessgroup(  859): failed to open /acct/uid_1000/pid_7253/cgroup.procs: No such file or directory
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 23.581ms
I/SystemConfig( 7592): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7592): existFile = false
I/SystemConfig( 7592): canReadFile = false
I/SystemConfig( 7592): systemFeature RCS result false
D/SystemConfig( 7592): refreshRcsSupport() :false
I/art     (  859): Explicit concurrent mark sweep GC freed 24581(1264KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.249ms total 165.856ms
,I/LockScreenSettings( 7614): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7614): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7614): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7614): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7614): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7614): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 1940): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/art     ( 7410): CheckpointMarkThreadRoots callback created = 0xb042d520
,I/art     ( 7410): CheckpointMarkThreadRoots callback created = 0xb042d510
,I/ActivityManager(  859): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7642 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1940): UpdateCorporaTask done [took 81 ms] updated apps [took 81 ms] 
,I/ActivityManager(  859): Killing 7389:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  859): failed to open /acct/uid_10048/pid_7389/cgroup.procs: No such file or directory
,D/Finsky  ( 7642): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7642): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7642): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7642): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7642): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3252): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3252): created cursor android.database.sqlite.SQLiteCursor@1a214ffc on behalf of 7642
D/Finsky  ( 7642): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7642): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  859): Killing 6997:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/Ads     ( 7642): Skipping gmscore version check
W/libprocessgroup(  859): failed to open /acct/uid_10038/pid_6997/cgroup.procs: No such file or directory
,I/ActivityManager(  859): Killing 7472:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7439): android.os.DeadObjectException
,W/System.err( 7439): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7439): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7439): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7439): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7439): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7439): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7439): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7439): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7439): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7439): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7439): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7439): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 7439): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7439): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7439): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7439): android.os.DeadObjectException
W/System.err( 7439): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7439): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7439): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7439): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7439): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7439): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7439): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7439): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7439): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7439): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7439): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7439): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7439): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7439): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7439): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  859): failed to open /acct/uid_10089/pid_7472/cgroup.procs: No such file or directory
,W/ActivityManager(  859): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/Finsky  ( 7642): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  859): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7689 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PackageBroadcastService( 4217): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4217): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7642): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4217): updateResources: need to parse f{com.google.android.gms}
,D/UEI.SmartControl( 7689): Quickset Services start...
,I/UEI.SmartControl( 7689): Manufacture = LGE
,D/UEI.SmartControl( 7689): File observer start...
E/UEI.SmartControl( 7689): IR Port is disabled: false
D/UEI.SmartControl( 7689): Starting file observer...
D/UEI.SmartControl( 7689): Extracting JNI libs...
D/UEI.SmartControl( 7689): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7689): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7689): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7689): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7689): --- Selecting new region: 2
I/UEI.SmartControl( 7689): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7689): Platform has CIR...
D/UEI.SmartControl( 7689): NO CIR support, need to check package...
I/UEI.SmartControl( 7689): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7689): QS Service created
E/UEI.SmartControl( 7689): QS start get config
,D/UEI.SmartControl( 7689): Loading JNI Libs...
,D/UEI.SmartControl( 7689):  configuring local db...
D/UEI.SmartControl( 7689):  ---- Has DB8: true
,D/UEI.SmartControl( 7689): QS start statue = true Error code = 0
D/UEI.SmartControl( 7689): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7689): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7689): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7689): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 7689): IrrcClient ++ 
D/irrcClient( 7689): getIrrcService ++ 
D/irrcClient( 7689): getIrrcService -- 
D/irrcClient( 7689): IrrcClient -- 
W/irrc_jni( 7689): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7689): Services init done
,I/UEI.SmartControl( 7689): Device manager: loading config....
D/UEI.SmartControl( 7689): QS Service init finished
D/UEI.SmartControl( 7689): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7689): Config is loaded...
D/UEI.SmartControl( 7689): QS Service version code: 1073
D/UEI.SmartControl( 7689): Service requested: Control
D/UEI.SmartControl( 7689): -----IControl: 11
D/UEI.SmartControl( 7689): Caller: com.lge.qremote
D/UEI.SmartControl( 7689): ------------ IControl registerCallback...
D/UEI.SmartControl( 7689): Internal service binding...
I/UEI.SmartControl( 7689): Registering callback...
,D/UEI.SmartControl( 7689): -----IControl: 19
D/UEI.SmartControl( 7689): Caller: com.lge.qremote
I/UEI.SmartControl( 7689): Registering Services Ready callback...
I/UEI.SmartControl( 7689): Notify client services are ready...
D/UEI.SmartControl( 7689): -----IControl: 8
D/UEI.SmartControl( 7689): Caller: com.lge.qremote
I/AudioManager( 7439): getMode name:com.lge.qremote
,I/AudioManager( 7439): getMode name:com.lge.qremote
,I/AudioManager( 7439): getMode name:com.lge.qremote
D/UEI.SmartControl( 7689):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7689): Notify AllClients services are ready: 0
D/PowerService( 1807): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  859): battery changed pluggedType: 2
D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
,D/LEDHandler( 1807): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/charger_monitor(  483): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,I/Icing   ( 4217): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Icing   ( 4217): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  859): Killing 7544:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  859): failed to open /acct/uid_10011/pid_7544/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
I/ActivityManager(  859): Killing 7286:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  859): failed to open /acct/uid_10061/pid_7286/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7689): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 134801460995; DSPS: 4515076; Offset : -2998724015
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PowerManagerServiceEx(  859): acquireWakeLockInternal: lock=78664432, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=859
,D/WeatherService( 2572): 2 : TimeTick Intent has been received, Time(hour:min:sec) 11:51:0
,D/WeatherService( 2572): 2 : TimeTick Intent And Screen On
D/WeatherService( 2572): 2 : SDK version : 21
W/ActivityManager(  859): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2572): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2572): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2572): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2572): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2572): 2 : This is isUpdating : false
D/WeatherService( 2572): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2572): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2572): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2572): 2 : Fixed theme : optimus
I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
D/WeatherReflect( 2572): 2 : Map key string is -2
,I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
,I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/lim     ( 2572): 2 : time = 11:51
I/WeatherReflect( 2572): Model Name : LG-D722
D/WeatherTheme( 2572): 2 : Different view - status_min_formatted : 50 != 51
D/WeatherTheme( 2572): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2572): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2572): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2572): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2572): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2572): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2572): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2572): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2572): forecast size is 0
,D/Theme   ( 2572): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2572): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2572): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2572): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2572): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2572): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2572): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2572): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2572): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2572): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2572): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2572): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2572): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2572): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2572): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2572): url is : null
D/Theme   ( 2572): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2572): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2572): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2572): 2 : update view, appWidgetId: 2
D/WeatherService( 2572): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 11:51:0
,D/PowerManagerServiceEx(  859): releaseWakeLockInternal: lock=78664432 [*alarm*], flags=0x0
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{df8a069 type 2 when 145700 com.google.android.gms} when 145700
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1735): Vacuum at: now=1452509462623 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  859): ALS enabled for SRE
D/PowerManagerServiceEx(  859): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29046 ms ago)
,D/qdlights(  859): set_light_backlight: 254
,D/qdlights(  859): set_light_backlight: 251
D/qdlights(  859): set_light_backlight: 248
,D/qdlights(  859): set_light_backlight: 244
,D/qdlights(  859): set_light_backlight: 241
,D/qdlights(  859): set_light_backlight: 238
,D/qdlights(  859): set_light_backlight: 234
,D/qdlights(  859): set_light_backlight: 231
,D/qdlights(  859): set_light_backlight: 228
,D/qdlights(  859): set_light_backlight: 224
,D/qdlights(  859): set_light_backlight: 221
,D/qdlights(  859): set_light_backlight: 218
,D/qdlights(  859): set_light_backlight: 214
,D/qdlights(  859): set_light_backlight: 211
,D/qdlights(  859): set_light_backlight: 208
,D/qdlights(  859): set_light_backlight: 204
,D/qdlights(  859): set_light_backlight: 201
,D/qdlights(  859): set_light_backlight: 198
,D/qdlights(  859): set_light_backlight: 194
,D/qdlights(  859): set_light_backlight: 191
,D/qdlights(  859): set_light_backlight: 188
,D/qdlights(  859): set_light_backlight: 184
,D/qdlights(  859): set_light_backlight: 181
,D/qdlights(  859): set_light_backlight: 178
,D/qdlights(  859): set_light_backlight: 174
,D/qdlights(  859): set_light_backlight: 171
,D/qdlights(  859): set_light_backlight: 168
,D/qdlights(  859): set_light_backlight: 164
,D/qdlights(  859): set_light_backlight: 161
,D/qdlights(  859): set_light_backlight: 158
,D/qdlights(  859): set_light_backlight: 154
,D/qdlights(  859): set_light_backlight: 151
,D/qdlights(  859): set_light_backlight: 148
,D/qdlights(  859): set_light_backlight: 144
,D/qdlights(  859): set_light_backlight: 141
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  859): set_light_backlight: 138
,D/qdlights(  859): set_light_backlight: 134
,D/qdlights(  859): set_light_backlight: 131
,D/qdlights(  859): set_light_backlight: 128
,D/qdlights(  859): set_light_backlight: 124
,D/qdlights(  859): set_light_backlight: 121
,D/qdlights(  859): set_light_backlight: 118
,D/qdlights(  859): set_light_backlight: 114
,D/qdlights(  859): set_light_backlight: 111
,D/qdlights(  859): set_light_backlight: 108
,D/qdlights(  859): set_light_backlight: 104
,D/qdlights(  859): set_light_backlight: 101
,D/qdlights(  859): set_light_backlight: 98
,D/qdlights(  859): set_light_backlight: 94
,D/qdlights(  859): set_light_backlight: 91
,D/qdlights(  859): set_light_backlight: 88
,D/qdlights(  859): set_light_backlight: 84
,D/qdlights(  859): set_light_backlight: 81
,D/qdlights(  859): set_light_backlight: 78
,D/qdlights(  859): set_light_backlight: 74
,D/qdlights(  859): set_light_backlight: 71
,D/qdlights(  859): set_light_backlight: 68
,D/qdlights(  859): set_light_backlight: 64
,D/qdlights(  859): set_light_backlight: 61
,D/qdlights(  859): set_light_backlight: 58
,D/qdlights(  859): set_light_backlight: 54
,D/qdlights(  859): set_light_backlight: 51
,D/qdlights(  859): set_light_backlight: 48
,D/qdlights(  859): set_light_backlight: 44
,D/qdlights(  859): set_light_backlight: 41
,D/qdlights(  859): set_light_backlight: 38
,D/qdlights(  859): set_light_backlight: 34
,D/qdlights(  859): set_light_backlight: 31
,D/qdlights(  859): set_light_backlight: 28
,D/qdlights(  859): set_light_backlight: 24
,D/qdlights(  859): set_light_backlight: 21
,D/qdlights(  859): set_light_backlight: 18
,D/qdlights(  859): set_light_backlight: 14
,D/qdlights(  859): set_light_backlight: 11
,D/qdlights(  859): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 154802211144; DSPS: 5170461; Offset : -2998736805
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  859): ALS enabled for SRE
D/PowerManagerServiceEx(  859): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36036 ms ago)
I/PowerManagerService(  859): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  859): ALS enabled for SRE
D/PowerManagerServiceEx(  859): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36048 ms ago)
,W/ContextImpl(  859): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  859): Sleeping (uid 1000)...
D/LPWGController(  859): [updateScreenState] screen on = false
,D/LPWGController(  859): disable proximity sensor
D/LPWGController(  859): enable proximity sensor
I/SensorManager(  859): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3eaf9c6] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  859): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  859): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  859): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  859): activate: handle is 48, enable
V/sensors_hal_Ctx(  859): activate sensors is 1400000000000
D/sensors_hal_Thresh(  859): enable: handle=48
I/sensors_hal_SAM(  859): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  859): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  859): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  859): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  859): enable: Received response: 0
D/PowerManagerServiceEx(  859): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36093 ms ago)
I/Adreno-EGL(  859): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  859): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  859): Build Date: 03/02/15 Mon
I/Adreno-EGL(  859): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  859): Remote Branch: 
I/Adreno-EGL(  859): Local Patches: 
I/Adreno-EGL(  859): Reconstruct Branch: 
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1047 us)
,I/Sensors (  429): sns_pwr.c(273):acquiring wakelock
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
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/qdlights(  859): set_light_backlight: 0
,I/SensorManager(  859): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  859): activate: handle is 46, disable
V/sensors_hal_Ctx(  859): activate sensors is 1000000000000
D/sensors_hal_LP2(  859): enable: handle=46
D/sensors_hal_LP2(  859): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  859): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  859): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  859): Display changed displayId=0
,V/sensors_hal_SAM(  859): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  859): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1753): Display #0 changed.
D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  859): Excessive delay in setPowerMode(): 230ms
I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  859): Got set_interactive hint
,D/KeyguardViewMediator( 1375): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
D/KeyguardViewMediator( 1375): notifyScreenOffLocked
D/KeyguardViewMediator( 1375): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1375): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1375): unregisterProximitySensor
,D/StatusBarWindowView( 1375): onScreenTurnedOff why = 3
,D/WifiServerServiceExt(  859): sendKtScanInterval  mRtspPlay : false
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/AudioFlinger(  289): setParameters(): io 0, keyvalue screen_state=on, calling pid 859
,D/audio_hw_primary(  289): adev_set_parameters: enter: screen_state=on
V/voice   (  289): voice_set_parameters: enter: screen_state=on
V/compress_voip(  289): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  289): voice_extn_compress_voip_set_parameters: exit
V/voice   (  289): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  289): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  289): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  289): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  289): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  289): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  289): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  289): adev_set_parameters: exit with code(0)
I/WifiServerServiceExt(  859): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
,D/GpsLocationProvider(  859): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1842): |CORE| sendScreenState: state:true
I/LEDService( 1807): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1807): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1807): stopPatternFlashing()
D/Cliptray Service( 1807): lockStatus = 0
D/qdlights( 1807): set_light_notifications: 0,0,0,0,3
I/LEDService( 1807): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1807): set_light_notifications: 0,0,0,0,3
I/LEDService( 1807): updateLightsLocked : turn off led
D/qdlights( 1807): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1807): RESTART MSG
D/SplitWindow(  859): check instance of lgWin Window{314228dd u0 SearchPanel}
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
,D/InputDispatcher(  859): Window went away: Window{3f5a26a3 u0 SearchPanel}
I/[SystemUI]Clock( 1375): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
,D/Ulp_jni (  859): JNI:system_update. Event-0
,I/Sensors (  429): sns_pwr.c(301):releasing wakelock
,I/art     ( 1735): Explicit concurrent mark sweep GC freed 41276(2MB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 13MB/22MB, paused 1.768ms total 102.740ms
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2572): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:51:14
,D/WeatherService( 2572): 2 : ACTION screen on
,D/WeatherService( 2572): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2572): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2572): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:51:14
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): ACTION_SCREEN_ON
D/AppCleanupService( 4085): android.intent.action.SCREEN_ON
,V/AudioFlinger(  289): setParameters(): io 0, keyvalue screen_state=off, calling pid 859
D/audio_hw_primary(  289): adev_set_parameters: enter: screen_state=off
V/voice   (  289): voice_set_parameters: enter: screen_state=off
V/compress_voip(  289): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  289): voice_extn_compress_voip_set_parameters: exit
V/voice   (  289): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  289): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  289): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  289): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  289): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  289): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  289): adev_set_parameters: exit with code(0)
D/WifiController(  859): CMD_SCREEN_OFF 
D/WifiController(  859): shouldWifiStayAwake TRUE
,D/GpsLocationProvider(  859): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1842): |CORE| sendScreenState: state:false
,I/LEDService( 1807): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1807): stopPatternFlashing()
D/qdlights( 1807): set_light_notifications: 0,0,0,0,3
I/LEDService( 1807): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1807): set_light_notifications: 0,0,0,0,3
I/LEDService( 1807): updateLightsLocked : turn on led
D/VolumeVibrator( 1807): clear
I/Cliptray Service( 1807): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
E/LEDService( 1807): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1807): Can't handle this request of patternId:0
D/LEDHandler( 1807): RESTART MSG
,D/LNfcService( 1789): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1789): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1880): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2572): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:51:14
D/WeatherService( 2572): 2 : ACTION screen off
D/WeatherService( 2572): 2 : TimeTick Receiver Unregister
D/WeatherService( 2572): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:51:14
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  859): ACTION_SCREEN_OFF
D/AppCleanupService( 4085): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4085): AppUsageStatsSaveTask
E/NxpNfcJni( 1789): getReconnectState = 0x0
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
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{198cec52 type 2 when 162043 com.android.systemui} when 162043
,D/KeyguardViewMediator( 1375): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1753): getCallState : 0
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1375): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1375): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 174803107281; DSPS: 5825850; Offset : -2998725601
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1807): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  859): battery changed pluggedType: 2
,I/ClearcutLoggerApiImpl( 1735): disconnect managed GoogleApiClient
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{2a6dcb23 type 2 when 188046 com.google.android.gms} when 188046
,I/PhenotypeConfigurator( 1735): Scheduling Phenotype for one-off execution 5743 seconds from now (1452509505009)
,D/GetConfigurationSnapshotOperation( 1735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1735): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  859): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  283): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  283): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  283): res_queryN name = xxxxx succeed
,I/System.out( 1735): propertyValue:false
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  859): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{33030b38 type 2 when 189288 android} when 189288
,D/LocationManagerService(  859): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  859): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  283): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  283): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  283): res_queryN name = xxxxx succeed
I/System.out( 1735): propertyValue:false
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  859): android: cancelAsUser(2) by android
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
D/LocationManagerService(  859): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  859): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  859): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 194803800399; DSPS: 6481233; Offset : -2998734699
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 214804546589; DSPS: 7136617; Offset : -2998720540
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/PowerService( 1807): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  859): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  859): battery changed pluggedType: 2
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 234805219238; DSPS: 7791999; Offset : -2998720346
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1807): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 254805890220; DSPS: 8447381; Offset : -2998719788
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 274806644691; DSPS: 9102766; Offset : -2998728334
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 294807318278; DSPS: 9758148; Offset : -2998726133
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1807): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 314807992541; DSPS: 10413530; Offset : -2998723153
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 334808719564; DSPS: 11068914; Offset : -2998728473
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6142): --= Surplus to requirements =--
I/jxcore-log( 6142): 
I/jxcore-log( 6142): ****TEST TOOK:  ms ****
I/jxcore-log( 6142): 
I/jxcore-log( 6142): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6142): 
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1807): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,D/PowerService( 1807): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  859): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  859): battery changed pluggedType: 2
D/AndroidRuntime( 7883): 
D/AndroidRuntime( 7883): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7883): CheckJNI is OFF
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/AndroidRuntime( 7883): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  859): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  859): Killing 6142:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,W/PackageSettings(  859): Skipping PackageSetting{2ea04c6d com.example.hello/10317} due to missing metadata
,I/WindowState(  859): WIN DEATH: Window{3a5944ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  859): Focus left window: Window{3a5944ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  859): Window went away: Window{3a5944ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  859):   Force finishing activity ActivityRecord{36f941ac u0 com.test.thalitest/.MainActivity t220}
,V/ActivityManager(  859): Display changed displayId=0
,D/DSDPConnection( 1753): Display #0 changed.
W/ActivityManager(  859): Spurious death for ProcessRecord{3ea00950 6142:com.test.thalitest/u0a316}, curProc for 6142: null
,I/ActivityManager(  859): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  859):   Force finishing activity ActivityRecord{36f941ac u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  859): Duplicate finish request for ActivityRecord{36f941ac u0 com.test.thalitest/.MainActivity t220 f}
,I/[LGHome]EVENT( 1880): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  859): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1880): [Launcher.java:776:onResume()]onResume
W/GeofencerStateMachine( 1735): Ignoring removeGeofence because network location is disabled.
,W/System.err( 3629): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3629): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3629): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3629): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3629): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3629): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3629): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3629): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3629): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3629): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3629): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3629): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  859): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7930 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/art     ( 1940): Explicit concurrent mark sweep GC freed 9556(557KB) AllocSpace objects, 4(96KB) LOS objects, 40% free, 12MB/21MB, paused 16.552ms total 158.352ms
I/[LGHome]EVENT( 1880): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1880): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1880): [Launcher.java:929:onResume()]onResume end
I/Activity( 1880): Activity.onPostResume() called 
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
,D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
I/art     ( 4217): Explicit concurrent mark sweep GC freed 4042(212KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 14MB/18MB, paused 1.077ms total 201.383ms
,D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
,D/KeyguardModel( 1375): handleShortcutListChanged...
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
,W/[LGHome]LGWallpaperInfo( 1880): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1880): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
,W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/SystemUI[Framework](  859): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
D/InputDispatcher(  859): Focus entered window: Window{33c5b97 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,W/PhoneWindowManagerEx(  859): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  859): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  859): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3555b1f3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  859): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  859): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  859): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  859): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3555b1f3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
D/KeyguardModel( 1375): handleShortcutListChanged...
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1880): [setNavigationBarColor] color=0x 0
W/ResourcesManager( 7930): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7930): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7930): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/art     (  859): Explicit concurrent mark sweep GC freed 67156(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 6.660ms total 375.051ms
,I/art     (  859): WaitForGcToComplete blocked for 254.935ms for cause Explicit
I/LGEmail ( 7930): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/administrator(  859): Handling package changes for user 0
,D/LGEmail ( 7930): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/InputMethodManagerService(  859): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  859): Got RemoteException sending setActive(false) notification to pid 6142 uid 10316
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  859): Timeline: Activity_windows_visible id: ActivityRecord{14992e1 u0 com.lge.launcher2/.Launcher t219} time:345089
W/IInputConnectionWrapper( 1880): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1592): Unable to connect to the editor to retrieve text... will retry later
I/art     (  859): Explicit concurrent mark sweep GC freed 7871(453KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.221ms total 420.996ms
I/NotificationService(  859): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  859): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  859): Receieved: android.intent.action.PACKAGE_REMOVED
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PhoneStatusBar( 1375): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
D/TaskPersister(  859): removeObsoleteFile: deleting file=220_task.xml
D/PowerService( 1807): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/art     ( 1789): Background sticky concurrent mark sweep GC freed 69498(4MB) AllocSpace objects, 0(0B) LOS objects, 29% free, 9MB/14MB, paused 6.202ms total 33.202ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/PackageChangeReceiver( 7930): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1880): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
I/ActivityManager(  859): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7959 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  859): Killing 7566:com.android.gallery3d/u0a23 (adj 15): empty #11
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/AndroidRuntime( 7883): Shutting down VM
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1789): getDefaultRoute
W/libprocessgroup(  859): failed to open /acct/uid_10023/pid_7566/cgroup.procs: No such file or directory
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  859): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  859): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  859): battery changed pluggedType: 2
,I/AppUp4:AppBoxCP( 7959): onCreate
W/AppUp4:DB( 7959):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7959):  setFingerPrint start
I/AppUp4:DB( 7959):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7959):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7959):  SDK version = 0
I/AppUp4:DB( 7959):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7959): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 7959): added Exclude : com.test.thalitest
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager(  859): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  859): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7976 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  859): Killing 7065:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  859): failed to open /acct/uid_10006/pid_7065/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourceType(  859): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline( 1880): Timeline: Activity_idle id: android.os.BinderProxy@c68a7e time:345684
,I/art     ( 1880): Explicit concurrent mark sweep GC freed 27365(1499KB) AllocSpace objects, 19(2MB) LOS objects, 40% free, 15MB/25MB, paused 1.004ms total 58.487ms
,W/ResourcesManager( 7976): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
