#### Test 50650278e989a4f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/GAV2    ( 5912): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/AndroidRuntime( 6151): 
D/AndroidRuntime( 6151): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6151): CheckJNI is OFF
D/AlertService( 5966): Beginning updateAlertNotification
D/AlertService( 5966): No fired or scheduled alerts
I/NotificationManager( 5966): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5966): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5966): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5966): No events found starting within 1 week.
--------- beginning of system
I/ActivityManager(  974): Killing 5966:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  974): failed to open /acct/uid_10013/pid_5966/cgroup.procs: No such file or directory
I/ActivityManager(  974): Killing 5683:com.google.android.talk/u0a61 (adj 15): empty #11
I/ThermalEngine(  287): Sensor:pa_therm0:31000 mC
W/libprocessgroup(  974): failed to open /acct/uid_10061/pid_5683/cgroup.procs: No such file or directory
D/AndroidRuntime( 6151): Calling main entry com.android.commands.am.Am
I/ActivityManager(  974): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  974): setTaskToReturnTo : TaskRecord{154d7204 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  974): setTaskToReturnTo : TaskRecord{154d7204 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  974): AppWindowTokenEx init.. 
D/ContextHelper(  974): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  974): Focus left window: Window{2a8553d4 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6151): Shutting down VM
D/SplitWindow(  974): check instance of lgWin Window{bfbe90f u0 Starting com.test.thalitest}
D/Finsky  ( 6050): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  974): RTC_WAKEUP set : Alarm{2bdefd9c type 0 when 1450233023850 com.android.vending} when 1450233023850
I/ActivityManager(  974): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6172 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/HotwordDetector( 1944): Closing mic
I/MicrophoneInputStream( 1944): mic_close com.google.android.apps.gsa.speech.audio.u@cc69fbd
V/AudioRecord( 1944): stop()
D/AudioRecord( 1944): AudioRecord->stop()
I/NotificationManager(  974): android: cancelAsUser(2) by android
V/AudioFlinger(  274): RecordHandle::stop()
V/AudioFlinger(  274): RecordThread::stop
V/AudioFlinger(  274): Record stopped OK
V/AudioPolicyManager(  274): stopInput() input 16
V/AudioPolicyService(  274): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  274): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  274): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  274): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  274): ThreadBase::setParameters() routing=0
V/AudioFlinger(  274): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  274): processConfigEvents_l() remaining events 1
V/AudioFlinger(  274): processConfigEvents_l() DONE thread 0xb4393000
D/audio_hw_primary(  274): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  974): Starting window displayed
I/SystemUI[Framework](  974): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1376): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  974): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  974): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  974): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  974): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@30e8a2ef,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  974): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1376): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1376):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1376): , Keyguard show=false, IME shown=false, Panel expanded=false
V/audio_hw_primary(  274): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  274): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  274): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  274): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  274): disable_audio_route: exit
E/audio_hw_primary(  274): disable_snd_device: enter 144
D/hardware_info(  274): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  274): disable_snd_device: snd_device(144: lg-vr-handset-mic)
D/BarTransitions( 1376): draw background and invalidate : color = c000000
V/audio_hw_primary(  274): stop_input_stream: exit: status(0)
V/audio_hw_primary(  274): in_standby: exit:  status(0)
V/AudioFlinger(  274): RecordThread: loop stopping
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
V/AudioPolicyManager(  274): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  274): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  274): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  274): inserting command: 10 at index 0, num commands 0
D/BarTransitions( 1376): draw background and invalidate : color = 11111111
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
V/AudioPolicyService(  274): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  274): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  274): setParameters(): io 16, keyvalue hotword_active=0, calling pid 274
V/AudioFlinger(  274): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  274): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  274): RecordThread: loop starting
V/AudioFlinger(  274): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  274): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  274): in_set_parameters: exit: status(0)
,V/AudioFlinger(  274): processConfigEvents_l() DONE thread 0xb4393000
V/AudioFlinger(  274): RecordThread: loop stopping
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
V/AudioRecord( 1944): stop()
,V/AudioRecord( 1944): stop()
V/AudioRecord( 1944): stop()
V/AudioFlinger(  274): RecordHandle::stop()
V/AudioFlinger(  274): RecordThread::stop
V/AudioPolicyManager(  274): releaseInput() 16
V/AudioPolicyManager(  274): closeInput(16)
V/AudioFlinger(  274): releasing 15 from 1944 for -1
V/AudioFlinger(  274):  decremented refcount to 0
V/AudioFlinger(  274): purging stale effects
V/AudioFlinger(  274): closeInput() 16
V/AudioSystem(  274): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1944): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  274): ThreadBase::exit
V/AudioSystem(  974): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  274): RecordThread: loop starting
V/AudioSystem( 1376): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2792): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  274): RecordThread 0xb4393000 exiting
V/AudioSystem( 1752): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1968): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 3198): ioConfigChanged() event 4, ioHandle 16
D/audio_hw_primary(  274): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  274): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  274): in_standby: exit:  status(0)
V/AudioPolicyService(  274): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  274): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  274): releaseInput() exit
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioFlinger(  274): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  274): removeClient_l() pid 1944, calling pid 274
V/AudioPolicyService(  274): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1944): Stopping hotword detection.
I/HotwordRecognitionRnr( 1944): Hotword detection finished
,D/ContextHelper( 6172): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,D/libc-netbsd( 6050): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6050): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6050): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6050): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  270): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out( 6050): propertyValue:false
D/libc-netbsd( 6050): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6050): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6050): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6050): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/WebViewFactory( 6172): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6172): Time to load native libraries: 4 ms (timestamps 4127-4131)
,I/LibraryLoader( 6172): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6172): Binding Chromium to main looper Looper (main, tid 1) {3d7876fc}
,I/LibraryLoader( 6172): Expected native library version number "",actual native library version number ""
I/chromium( 6172): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6172): Initializing chromium process, singleProcess=true
,W/art     ( 6172): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6172): ApplicationContext is null in ApplicationStatus
W/chromium( 6172): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6172): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6172): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6172): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6172): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6172): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6172): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6172): Remote Branch: 
I/Adreno-EGL( 6172): Local Patches: 
I/Adreno-EGL( 6172): Reconstruct Branch: 
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  974): android: cancelAsUser(2) by android
,V/AudioPolicyService(  274): registerClient() client 0xb3c3ce20, uid 10316
,I/qtaguid ( 6050): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6050): Untagging socket 41 failed errno=-22
,W/NetworkManagementSocketTagger( 6050): untagSocket(41) failed with errno -22
D/Finsky  ( 6050): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
D/BluetoothManagerService(  974): Message: 20
D/BluetoothManagerService(  974): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22031aef:true
D/BluetoothAdapterService(5506792)( 1968): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1bb597e
,I/ActivityManager(  974): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6226 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  974): android: cancelAsUser(2) by android
,W/art     ( 6172): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6172): onDetachedFromWindow called when already detached. Ignoring
,W/ResourcesManager( 6226): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6226): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/SystemWebViewEngine( 6172): CordovaWebView is running on device made by: LGE
,W/art     ( 6172): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6172): Attempt to remove local handle scope entry from IRT, ignoring
,I/MultiDex( 6226): VM with version 2.1.0 has multidex support
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/MultiDex( 6226): install
I/MultiDex( 6226): VM has multidex support, MultiDex support library is disabled.
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Activity( 6172): Activity.onPostResume() called 
,I/qtaguid ( 6050): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6050): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6050): untagSocket(41) failed with errno -22
V/JNIHelp ( 6226): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/OpenGLRenderer( 6172): Render dirty regions requested: true
I/OpenGLRenderer( 6172): Initialized EGL, version 1.4
D/OpenGLRenderer( 6172): Enabling debug mode 0
,D/Atlas   ( 6172): Validating map...
,D/SplitWindow(  974): check instance of lgWin Window{284f4730 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6172): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/ActivityThread( 6226): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6226): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@25356ede: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6226): Installed default security provider GmsCore_OpenSSL
,D/InputDispatcher(  974): Focus entered window: Window{284f4730 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/NotificationManager( 6226): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6226): com.google.android.gms: cancel(39789) by com.google.android.gms
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 94776572310; DSPS: 3204242; Offset : -3014635573
D/WearableService( 1734): callingUid 10006, callindPid: 1734
,E/MDM     ( 1734): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 6226): Reading stored module config
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4203): Restart initialization of location
W/InputMethodManagerService(  974): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  974): Displayed com.test.thalitest/.MainActivity: +1s224ms
I/Timeline(  974): Timeline: Activity_windows_visible id: ActivityRecord{1dcef3ed u0 com.test.thalitest/.MainActivity t220} time:94825
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
I/Timeline( 6172): Timeline: Activity_idle id: android.os.BinderProxy@1ab859fb time:94840
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
,D/ChimeraCfgMgr( 6226): Loading module com.google.android.gms.car from APK com.google.android.gms
W/BindingManager( 6172): Cannot call determinedVisibility() - never saw a connection for the pid: 6172
,D/CAR.SERVICE( 6226): Connecting to CarCallService...
,D/NativeLibraryUtils( 6226): Install completed successfully. count=14 extracted=0
I/art     ( 6050): CheckpointMarkThreadRoots callback created = 0xb05688b0
,I/art     ( 6226): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6226): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6050): CheckpointMarkThreadRoots callback created = 0xb0568880
D/JsMessageQueue( 6172): Set native->JS mode to OnlineEventsBridgeMode
,D/CAR.SERVICE( 6226): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6226): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6226): Creating a new PhoneAdapter instance
W/ActivityManager(  974): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6226): setListener: com.google.android.gms.car.dn@37e8db45
W/ActivityManager(  974): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6226): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6226): Starting CarCallService with initial phone null
I/NotificationManager( 6226): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6226): Package validated; name: com.android.vending
,I/NotificationManager( 6050): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6050): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/jxcore_app_log( 6172): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622764032
,D/JX-Cordova( 6172): jxcore cordova android initializing
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  974): android: cancelAsUser(2) by android
,I/art     ( 6172): CheckpointMarkThreadRoots callback created = 0x9ba303a0
,I/art     ( 6172): CheckpointMarkThreadRoots callback created = 0x9ba30370
,I/qtaguid ( 6050): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6050): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6050): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6050): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6050): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6050): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6050): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 6050): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  974): RTC_WAKEUP set : Alarm{2299a6cb type 0 when 1450233026767 com.android.vending} when 1450233026767
,D/Finsky  ( 6050): [750] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1734): client connected with version: 8296000
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  974): android: cancelAsUser(2) by android
,D/libc-netbsd( 6050): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6050): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6050): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6050): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  270): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
,I/System.out( 6050): propertyValue:false
I/art     (  974): Explicit concurrent mark sweep GC freed 32698(1547KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.286ms total 206.185ms
,W/jxcore-log( 6172): Initializing JXcore engine
,W/jxcore-log( 6172): JXcore engine is ready
W/jxcore-log( 6172): Starting JXcore engine
,W/.test.thalitest( 6172): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5774]" dev="sockfs" ino=5774 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6172): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6172): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8299]" dev="sockfs" ino=8299 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6172): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6172): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6172): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[28480]" dev="sockfs" ino=28480 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/ActivityManager(  974): Process com.google.android.gm (pid 5912) has died
,W/jxcore-log( 6172): Platform android
W/jxcore-log( 6172): 
W/jxcore-log( 6172): Process ARCH arm
W/jxcore-log( 6172): 
I/ThermalEngine(  287): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  974): RTC_WAKEUP set : Alarm{3d762443 type 0 when 1450233029072 com.google.android.googlequicksearchbox} when 1450233029072
,W/art     ( 1944): Verification of void com.google.o.a.a.a.f.a(com.google.i.a.b) took 158.085ms
,I/jxcore-log( 6172): JXcore Cordova bridge is ready!
I/jxcore-log( 6172): 
W/jxcore-log( 6172): JXcore engine is started
,I/chromium( 6172): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 6172): Skipped 200 frames!  The application may be doing too much work on its main thread.
D/CAR.SERVICE( 6226): mConnectedToCar = false, abort
,E/ActivityThread( 6226): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3715478d that was originally bound here
E/ActivityThread( 6226): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3715478d that was originally bound here
E/ActivityThread( 6226): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6226): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6226): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6226): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6226): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6226): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6226): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6226): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6226): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6226): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6226): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6226): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6226): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6226): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6226): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6226): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6226): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6226): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6226): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6226): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6226): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6226): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6226): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@277b7fbc that was originally bound here
E/ActivityThread( 6226): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@277b7fbc that was originally bound here
E/ActivityThread( 6226): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6226): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6226): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6226): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6226): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6226): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6226): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6226): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6226): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6226): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6226): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6226): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6226): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6226): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6226): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6226): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6226): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6226): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6226): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6226): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6226): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  974): Unbind failed: could not find connection for android.os.BinderProxy@392c0ac0
I/jxcore-log( 6172): Toggling radios to true
I/jxcore-log( 6172): 
,D/BluetoothAdapter( 6172): enable(): BT is already enabled..!
D/WifiServiceImplEx(  974): setWifiEnabled: true pid=6172, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  974): setWifiEnabled: true pid=6172, uid=10316
D/WifiServiceImplEx(  974): disconnect pid=6172, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  974): reconnect pid=6172, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6172): Radios toggled
I/jxcore-log( 6172): 
D/BluetoothManagerService(  974): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6172): Got Device Bluetooth address: F8:95:C7:87:85:54
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): Perf Test app loaded loaded
I/jxcore-log( 6172): 
I/jxcore-log( 6172): check test folder
I/jxcore-log( 6172): 
I/jxcore-log( 6172): found test : ./testFindPeers.js
I/jxcore-log( 6172): 
,I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
I/jxcore-log( 6172): found test : ./testSendData.js
I/jxcore-log( 6172): 
I/wpa_supplicant( 2770): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/wpa_supplicant( 2770): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
E/WifiStateMachine(  974): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  974): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WfdsMonitor( 1796): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService(  974): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  974): P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  974): RunningState{ when=-5ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  270): Clearing all IP addresses on wlan0
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 7
,D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1734): Read error: ssl=0xaaee0e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1734): SSL shutdown failed: ssl=0xaaee0e00: I/O error during system call, Broken pipe
,D/WifiHS20(  974): hidePasspointNotification off =false
D/ConnectivityService(  974): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:31.621 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/ConnectivityService(  974): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService(  974): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): ValidatedState{ when=-6ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): DefaultState{ when=-16ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): Forcing reevaluation
,D/WifiServiceExtension( 1796): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
,I/ActivityManager(  974): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6331 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
E/WifiStateMachine(  974): Start Disconnecting Watchdog 1
D/WifiHS20(  974): hidePasspointNotification off =false
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  974): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  974): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2770): wlan0: CTRL-EVENT-SCAN-STARTED 
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:31.717 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/CommandListener(  270): Clearing all IP addresses on wlan0
,D/ConnectivityService(  974): Default network via Wi-Fi disconnect. stop DSQN
D/WifiHS20(  974): hidePasspointNotification off =false
D/DSQN    (  974): disableDataServiceNotify
D/WifiServiceExtension( 1796): isInternetCheckAvailable return false
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:31.741 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
D/DhcpStateMachine(  974): StoppedState
D/DhcpStateMachine(  974): StoppedState{ when=-28ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/DSQN    (  974): stop dsqn bin
D/WifiNetworkAgent(  974): NetworkAgent: NetworkAgent channel lost
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/chromium( 6172): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:31.762 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  974): hidePasspointNotification off =false
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  974): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  974):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  974):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:31.768 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  974): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  974): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/WifiServerServiceExt(  974): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  974): setSupplicantStateSCANNING
D/ConnectivityService(  974): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524292
D/Nat464Xlat(  974): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): Disconnected - quitting
D/CSLegacyTypeTracker(  974): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  974): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  974): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  974): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  974): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  974): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1839): |CORE| No family connected
D/ConnectivityService(  974): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  974): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  974): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  974): [LG_RESTRICTED] !!!isConnected  type  :1
D/WIFI    (  974): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  974):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  974): Removing idletimer
V/NetworkPolicy(  974): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  974): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
W/Settings(  974): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1752): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  974): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ResourcesManager( 6331): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6331): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6331): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6331): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6331): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/IndexDatabaseHelper( 6331): Using schema version: 115
,I/IndexDatabaseHelper( 6331): Index is fine
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
I/ActivityManager(  974): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6356 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  974): Killing 5836:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  974): failed to open /acct/uid_10018/pid_5836/cgroup.procs: No such file or directory
,I/PCSuite ( 6356): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6356): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6356): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
I/PCSuite ( 6356): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6356): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6356): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  974): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6378 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  974): Killing 5858:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  974): failed to open /acct/uid_10069/pid_5858/cgroup.procs: No such file or directory
,W/ResourcesManager( 6378): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6378): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6378): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6378): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6378): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6378): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6378): MmsConfig.loadFromResources
E/Babel_SMS( 6378): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6378): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6378): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6378): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6378): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6378): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6378): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6378): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6378): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6378): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6378): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6378): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6378): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6378): found sensor: LGE Orientation Sensor, handle=49
,D/SensorManager( 6378): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6378): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6378): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6378): found sensor: Motion Accel, handle=46
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2770): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
W/Settings( 6378): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6378): startup - clean
,D/LocSvc_java(  974): onReceive
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:32.892 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  974): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  974): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:32.898 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/Babel   ( 6378): deleted: false for 0
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/art     ( 6378): CheckpointMarkThreadRoots callback created = 0xb042d510
,I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2770): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
,D/WifiServerServiceExt(  974): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  974): setSupplicantStateASSOCIATED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  974): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  974): setSupplicantStateFOUR_WAY_HANDSHAKE
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:32.958 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:32.959 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2770): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2770): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/WifiServiceExtension(  974): setVHTCapabilityType  : false
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/WifiServerServiceExt(  974): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  974): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,I/WifiServiceExtension(  974): setSecurityType  : 2
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:33.004 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:33.011 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/art     ( 6378): CheckpointMarkThreadRoots callback created = 0xb042d4e0
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  974): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  974): Got NetworkAgent Messenger
D/ConnectivityService(  974): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  974): NetworkAgent connected
D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiServiceExtension( 1796): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I,/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
E/WifiConfigStore(  974): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/PCSuite ( 6356): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6356): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6356): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6378): Unsupported mime audio/x-lg-flac
,E/WifiConfigStore(  974): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/AudioCapabilities( 6378): Unsupported mime audio/adpcm
W/AudioCapabilities( 6378): Unsupported mime audio/g726
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6378): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6378): Unsupported mime audio/wma-voice
D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
W/VideoCapabilities( 6378): Unsupported mime video/mjpg
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 9
D/CommandListener(  270): Setting iface cfg
,D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/WifiStateMachine(  974): Start Dhcp Watchdog 2
D/DhcpStateMachine(  974): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  974): WaitBeforeStartState
D/WifiServerServiceExt(  974): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  974): setSupplicantStateGROUP_HANDSHAKE
W/VideoCapabilities( 6378): Unsupported mime video/theora
I/PCSuite ( 6356): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6356): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6356): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/ConnectivityService(  974): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6331): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
W/AudioCapabilities( 6378): Unsupported mime audio/evrc
W/AudioCapabilities( 6378): Unsupported mime audio/qcelp
W/VideoCapabilities( 6378): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6378): Unsupported mime audio/amr-wb-plus
D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
W/AudioCapabilities( 6378): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6378): Unsupported mime audio/evrc
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
E/WifiStateMachine(  974): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  974): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  974): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e705ee7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  974): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e705ee7 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  974): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  974): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  974): DHCP Start wake lock is acquired.
,D/CommandListener(  270): Setting iface cfg
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/VideoCapabilities( 6378): Unsupported mime video/mp4v-esdp
D/CommandListener(  270): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  974): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  974): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  974): setSupplicantStateCOMPLETED
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt(  974): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  974): setSupplicantStateCOMPLETED
D/ConnectivityService(  974): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  974): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  974): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
D/ConnectivityService(  974): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  974): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  974): ignoring duplicate network state non-change
D/ConnectivityService(  974): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  974): Adding iface wlan0 to network 101
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1796): isInternetCheckAvailable return false
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:33.176 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:33.181 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1796): isInternetCheckAvailable return false
E/WifiStateMachine(  974): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiHS20(  974): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:33.191 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  974): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
E/ConnectivityService(  974): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  974): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
,D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  974): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  270): netlink response contains error (File exists)
D/ConnectivityService(  974): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  974): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  974): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  974): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:33.203 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Nat464Xlat(  974): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/WifiOffDelayIfNotUsed(  974): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService(  974): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  974): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  974): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  974):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  974):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  974):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  974):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  974):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  974): currentScore = 0, newScore = 20
D/ConnectivityService(  974):    accepting network in place of null
D/ConnectivityService(  974): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  974): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_,VPN] ]
D/WIFI    (  974):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1752): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): [LWD] Start DNSResolver start to wait,
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = true, mWifiLevel = 2
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/ConnectivityService(  974): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  974): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  974): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): [LWD] wait 500ms before dns check
D/ConnectivityService(  974): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
D/CSLegacyTypeTracker(  974): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  974): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/ConnectivityService(  974): validation of new default Network = false
D/ConnectivityService(  974): Default network via Wi-Fi connected. start DSQN
,D/DSQN    (  974): enableDataServiceNotify 
D/DSQN    (  974): start dsqn bin
W/QCNEJ   ( 1839): |CORE| No family connected
D/Tethering(  974): MasterInitialState.processMessage what=3
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  974): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  974):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  974):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  974): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524290
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/DSQN    ( 6415): DSQN samuel.seo ver 141203
E/DSQN    ( 6415): DSQN sock connect success to lgdatalistenerd
,I/DSQN    ( 6415): created command queue thread
I/DSQN    ( 6415): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6415): Interface wlan0 netmask 255.255.255.0 0xc0a80186
V/NetworkPolicy(  974): [LG_RESTRICTED] checkMobilePolicy_type()
I/VideoCapabilities( 6378): Unsupported profile 4 for video/mp4v-es
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
W/VideoCapabilities( 6378): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6378): Unrecognized profile 2130706433 for video/avc
D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/VideoCapabilities( 6378): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
W/VideoCapabilities( 6378): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6378): onServiceConnected
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
W/Babel   ( 6378): Attempted to change video mute state without an active call.
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/NotificationManager( 6378): com.google.android.talk: cancel(10436) by com.google.android.talk
D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
I/PCSuite ( 6356): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/DhcpStateMachine(  974): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  974): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  974): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/PCSuite ( 6356): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/AlarmManager(  974): ELAPSED_WAKEUP set : Alarm{36e1d552 type 2 when 103011 com.google.android.gms} when 103011
,I/dhcpcd  ( 6420): version 5.5.6 starting
E/dhcpcd  ( 6420): get_duid: Read-only file system
V/WiFiOffLoadBroadcast( 6331): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6331): MCCMNC not supported: null
I/PCSuite ( 6356): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6356): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  974): Killing 5527:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  270): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
,I/System.out( 1734): propertyValue:false
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  268): 
I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/libprocessgroup(  974): failed to open /acct/uid_10086/pid_5527/cgroup.procs: No such file or directory
I/DSQN    ( 6415): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6415): restart monitoring
,D/LGDataListener(  270): argv[0]=dsqncommand
D/LGDataListener(  270): argv[1]=wlan0
D/LGDataListener(  270): argv[2]=1
D/LGDataListener(  270): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6415): dsqn report finish
D/DSQN    (  974): DSQM DsqnNotification wlan0  1
D/DSQN    (  974): start to monitor internet connection
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/dhcpcd  ( 6420): wlan0: rebinding lease of 192.168.1.134
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  287): Sensor:pa_therm0:32000 mC
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): [LWD] DNSResolver start dns
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  270): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
,I/System.out(  974): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 02:30:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450233033814], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450233033789]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1796): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  974): Validated
D/ConnectivityService(  974): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  974): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  974):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  974):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  974):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  974): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  974): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  974):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  974):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  974): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  974): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  974): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  974): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/WifiServerServiceExt(  974): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  974): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1752): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  974):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/ProcessCpuTracker(  974): Skipping unknown process pid 6440
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  974): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/NotificationManager( 1944): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/dhcpcd  ( 6420): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6420): wlan0: leased 192.168.1.134 for 86400 seconds
,D/ConnectivityService(  974): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  974): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  974): onReceive
D/LocSvc_java(  974): got connectivity action
D/LocSvc_java(  974): broadcast - no network connections
D/LocSvc_java(  974): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  974): Sending msg: 4 arg1:0 arg2:1
,I/ActivityManager(  974): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6471 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LocSvc_java(  974): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  974): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  974): ignore wifi update if we are not in OPENING or CLOSING
,D/LocSvc_java(  974): onReceive
D/LocSvc_java(  974): got connectivity action
D/LocSvc_java(  974): broadcast - no network connections
D/LocSvc_java(  974): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  974): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  974): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  974): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  974): ignore wifi update if we are not in OPENING or CLOSING
,I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  974): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  974): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  974): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  974): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  974): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  974): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  974): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  974): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  974): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  974): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  974): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  974): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  974): RunningState
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  974): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:35.01 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  974): identical MTU - not setting
D/Nat464Xlat(  974): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  974): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  974):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  974):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  974): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  974): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  974): enableDataServiceNotify 
D/DSQN    (  974): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524295
D/DSQN    (  974): dsqn is running restart
,I/DSQN    ( 6497): DSQN samuel.seo ver 141203
E/DSQN    ( 6497): DSQN sock connect success to lgdatalistenerd
,I/DSQN    ( 6497): created command queue thread
I/DSQN    ( 6497): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6497): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/MusicStore( 6471): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6471): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  974): Process com.google.android.gms:car (pid 6226) has died
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6471): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6471): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6471): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6471): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6471): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6471): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6471): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34300231: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6471): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6471): GMSCore installation verified
,I/ConfigStore( 6471): Config Database version: 1
,I/MediaRouter( 6471): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6471): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6471): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6471): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  974): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6520 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6471): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6471): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6520): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6520): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6520): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationManager( 6471): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 6520): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6520): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-16 03:30:36.065 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/WifiInternetCheck(  974): Single check msg out of sync, ignoring.
,D/eas_req ( 6520): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/ConnectivityService(  974): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  974): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6549 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  974): Process com.android.vending (pid 6050) has died
I/HubEmail( 6520): JNI_OnLoad()
I/HubEmail( 6520): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6520): registerNatives()
I/HubEmail( 6520): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6520): registerNativeMethods()
I/HubEmail( 6520): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6520): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  974): onReceive
D/LocSvc_java(  974): got connectivity action
D/LocSvc_java(  974): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  974): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  974): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  974): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  974): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  974): ignore wifi update if we are not in OPENING or CLOSING
W/Settings( 6520): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/NetworkMonitor( 6471): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider(  974): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LGDMClient( 6549): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6549): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6549): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6549): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6549): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6549): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6549): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6549): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/jxcore-log( 6172): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6172): 
,I/ActivityManager(  974): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6574 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6549): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6549): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,I/art     (  337): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 22.059ms
D/LGDMClient( 6549): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6549): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6549): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6549): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  974): Killing 6117:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.738ms
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.149ms
,W/libprocessgroup(  974): failed to open /acct/uid_10014/pid_6117/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6574): onCreate
W/AppUp4:DB( 6574):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6574):  setFingerPrint start
I/AppUp4:DB( 6574):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6574):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6574):  SDK version = 0
I/AppUp4:DB( 6574):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6574): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6574): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6574): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6574): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6574): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6574): onReceive
I/AppUp4:CustModeStarterReceiver( 6574): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6574): Context : android.app.ReceiverRestrictedContext@2373a185
,D/AppUp4:CustFacade( 6574): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6574): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6574): begin check event
I/AppUp4:CustModeStarterReceiver( 6574): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6574): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6574): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6574): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6574): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  974): Killing 6331:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  974): failed to open /acct/uid_1000/pid_6331/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3198): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3198): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3198): networkInfo.isConnected() = false
I/ActivityManager(  974): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6593 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6593): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6593): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6593): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  974): Killing 5719:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
V/DownloadManager( 3218): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/CheckinService( 4203): Checkin interval check for package: unspecified last checkin: 1450233007619 min interval config: 0 actual interval: 29251
V/DownloadManager( 3218): DownloadService onCreate
,W/System.err( 5105): android.os.DeadObjectException
W/System.err( 5105): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5105): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5105): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5105): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
,W/System.err( 5105): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5105): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5105): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5105): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5105): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5105): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5105): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5105): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5105): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5105): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5105): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5105): android.os.DeadObjectException
W/System.err( 5105): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5105): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5105): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5105): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5105): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5105): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5105): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5105): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5105): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5105): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5105): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5105): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5105): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5105): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5105): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
D/PhoneMonitor( 6593): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6593): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6593): [parse] Load xml
,I/ActivityManager(  974): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6619 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,W/libprocessgroup(  974): failed to open /acct/uid_10089/pid_5719/cgroup.procs: No such file or directory
W/ActivityManager(  974): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/CheckinService( 4203): Checking schedule, now: 1450233036915 next: 1450233037583
I/CheckinService( 4203): active receiver: disabled
I/DownloadManager( 3218): in removeSpuriousFiles
V/TelephonyAutoProfiling( 6593): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
I/NotificationManager( 3218): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/TelephonyAutoProfiling( 6593): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3218): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/PhoneMonitor( 6593): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@3d3c08bf on behalf of 3218
,I/DownloadManager( 3218): in trimDatabase
V/DownloadManager( 3218): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@159c92d5 on behalf of 3218
I/ActivityManager(  974): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6645 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DownloadManager( 3218): DownloadService onStartCommand
V/DownloadManager( 3218): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@363271db on behalf of 3218
,V/DownloadManager( 3218): DownloadService onDestroy
,I/ActivityManager(  974): Killing 6356:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6645): Quickset Services start...
,I/UEI.SmartControl( 6645): Manufacture = LGE
D/UEI.SmartControl( 6645): File observer start...
E/UEI.SmartControl( 6645): IR Port is disabled: false
D/UEI.SmartControl( 6645): Starting file observer...
D/UEI.SmartControl( 6645): Extracting JNI libs...
D/UEI.SmartControl( 6645): --- this system supports 32-bit or 64-bit only
W/libprocessgroup(  974): failed to open /acct/uid_1000/pid_6356/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2775): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:30:37
D/UpdateThreadPoolManager( 2775): 2 : This is isUpdating : false
D/WeatherAncestor( 2775): connectivity changed - connection : true
D/Weather_cast( 2775): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2775): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:30:37
D/WeatherService( 2775): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  974): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2775): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2775): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2775): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/ActivityManager(  974): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6666 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6645): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6645): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6645): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/libc-netbsd( 6378): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6378): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6378): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6378): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  270): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out( 6378): propertyValue:false
I/UEI.SmartControl( 6645): --- Selecting new region: 2
I/UEI.SmartControl( 6645): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6645): Platform has CIR...
D/UEI.SmartControl( 6645): NO CIR support, need to check package...
I/UEI.SmartControl( 6645): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6645): QS Service created
I/DSQN    ( 6497): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6497): restart monitoring
D/LGDataListener(  270): argv[0]=dsqncommand
D/LGDataListener(  270): argv[1]=wlan0
D/LGDataListener(  270): argv[2]=1
,D/LGDataListener(  270): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6497): dsqn report finish
D/DSQN    (  974): DSQM DsqnNotification wlan0  1
D/DSQN    (  974): start to monitor internet connection
,I/Babel   ( 6378): connection state changed from UNKNOWN to CONNECTED
,E/UEI.SmartControl( 6645): QS start get config
D/UEI.SmartControl( 6645): Loading JNI Libs...
,D/UEI.SmartControl( 6645):  configuring local db...
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  270): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out(  974): propertyValue:false
,D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  974): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  974): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  270): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out(  974): propertyValue:false
V/WifiInternetCheck(  974): isHttpConnectionAvailable - We got a valid response : 204
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6666): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6666): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6666): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6666): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6666): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6666):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6666):   adb logcat -s GAv4
,W/GAv4    ( 6666): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/UEI.SmartControl( 6645):  ---- Has DB8: true
D/UEI.SmartControl( 6645): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6645): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6645): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6645): IRRCDataComm has AudioManager!!!!.
W/GAv4    ( 6666): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6666): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/irrc_jni( 6645): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6645): IrrcClient ++ 
D/irrcClient( 6645): getIrrcService ++ 
D/irrcClient( 6645): getIrrcService -- 
D/irrcClient( 6645): IrrcClient -- 
W/irrc_jni( 6645): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6645): Services init done
I/UEI.SmartControl( 6645): Device manager: loading config....
D/UEI.SmartControl( 6645): Config is loaded...
,I/ActivityManager(  974): Process com.google.android.music:main (pid 6471) has died
D/UEI.SmartControl( 6645): QS Service init finished
D/UEI.SmartControl( 6645): QS Service version name: 0.1.73
D/UEI.SmartControl( 6645): QS Service version code: 1073
D/UEI.SmartControl( 6645): Service requested: Control
,D/UEI.SmartControl( 6645): -----IControl: 11
D/UEI.SmartControl( 6645): Caller: com.lge.qremote
D/UEI.SmartControl( 6645): Internal service binding...
D/UEI.SmartControl( 6645): ------------ IControl registerCallback...
I/UEI.SmartControl( 6645): Registering callback...
D/UEI.SmartControl( 6645): -----IControl: 19
D/UEI.SmartControl( 6645): Caller: com.lge.qremote
I/UEI.SmartControl( 6645): Registering Services Ready callback...
D/UEI.SmartControl( 6645):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6645): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6645): -----IControl: 8
D/UEI.SmartControl( 6645): Caller: com.lge.qremote
I/WebViewFactory( 6666): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6666): Time to load native libraries: 1 ms (timestamps 7581-7582)
,I/LibraryLoader( 6666): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6666): Binding Chromium to main looper Looper (main, tid 1) {18894b8e}
I/LibraryLoader( 6666): Expected native library version number "",actual native library version number ""
I/chromium( 6666): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6666): Initializing chromium process, singleProcess=true
,W/art     ( 6666): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6666): ApplicationContext is null in ApplicationStatus
W/chromium( 6666): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6666): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6666): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6666): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6666): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6666): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6666): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6666): Remote Branch: 
I/Adreno-EGL( 6666): Local Patches: 
I/Adreno-EGL( 6666): Reconstruct Branch: 
V/AudioPolicyService(  274): registerClient() client 0xb4027060, uid 10079
,W/AudioManagerAndroid( 6666): Requires BLUETOOTH permission
I/art     (  974): Explicit concurrent mark sweep GC freed 81973(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.097ms total 184.182ms
,I/NSApplication( 6666): Starting up...
I/ActivityManager(  974): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6737 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  974): Killing 5105:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  974): failed to open /acct/uid_10106/pid_5105/cgroup.procs: No such file or directory
,I/ActivityManager(  974): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6757 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  974): Killing 6520:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  974): failed to open /acct/uid_10021/pid_6520/cgroup.procs: No such file or directory
,W/ResourcesManager( 6757): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  287): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  974): Killing 6549:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  974): failed to open /acct/uid_1000/pid_6549/cgroup.procs: No such file or directory
,I/ActivityManager(  974): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6781 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6781): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6781): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6781): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6781): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6781): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6781): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6781): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6781): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6781): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34300231: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6781): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6781): GMSCore installation verified
,I/ConfigStore( 6781): Config Database version: 1
,I/MediaRouter( 6781): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6781): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6781): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6781): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  974): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6809 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6781): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6781): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 6809): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6809): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6809): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  974): Killing 6574:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  974): failed to open /acct/uid_10011/pid_6574/cgroup.procs: No such file or directory
,I/NotificationManager( 6781): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6809): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6809): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6809): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  974): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6836 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6809): JNI_OnLoad()
I/HubEmail( 6809): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6809): registerNatives()
I/HubEmail( 6809): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6809): registerNativeMethods()
I/HubEmail( 6809): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6809): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  974): Killing 6593:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  974): failed to open /acct/uid_10038/pid_6593/cgroup.procs: No such file or directory
,W/Settings( 6809): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6836): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6836): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6836): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6836): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6836): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6836): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  974): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6861 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6836): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6836): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6836): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6836): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6836): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  974): Killing 6619:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  974): failed to open /acct/uid_10051/pid_6619/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6861): onCreate
,W/AppUp4:DB( 6861):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6861):  setFingerPrint start
I/AppUp4:DB( 6861):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6861):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6861):  SDK version = 0
I/AppUp4:DB( 6861):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6861): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6861): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6861): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6861): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6861): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6861): onReceive
I/AppUp4:CustModeStarterReceiver( 6861): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6861): Context : android.app.ReceiverRestrictedContext@2373a185
D/AppUp4:CustFacade( 6861): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6861): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6861): begin check event
I/AppUp4:CustModeStarterReceiver( 6861): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6861): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6861): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6861): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6861): handleAsyncCustNotification do not startCustService
I/ActivityManager(  974): Killing 6645:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  974): failed to open /acct/uid_10089/pid_6645/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3198): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3198): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3198): networkInfo.isConnected() = false
I/ActivityManager(  974): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6880 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  337): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 413us total 31.204ms
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 24.883ms
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 20.315ms
,D/PhoneMonitor( 6880): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6880): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6880): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  974): Killing 6378:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 6880): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6880): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6880): [parse] Load xml
,V/TelephonyAutoProfiling( 6880): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6880): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6880): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,W/libprocessgroup(  974): failed to open /acct/uid_10061/pid_6378/cgroup.procs: No such file or directory
,V/DownloadManager( 3218): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3218): DownloadService onCreate
I/NotificationManager( 3218): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3218): in removeSpuriousFiles
V/DownloadManager( 3218): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@1c3a7bb6 on behalf of 3218
I/DownloadManager( 3218): in trimDatabase
V/DownloadManager( 3218): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@3b5c50b7 on behalf of 3218
I/ActivityManager(  974): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6902 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3218): DownloadService onStartCommand
V/DownloadManager( 3218): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 4203): Checkin interval check for package: unspecified last checkin: 1450233007619 min interval config: 0 actual interval: 32943
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@3715478d on behalf of 3218
I/CheckinService( 4203): Checking schedule, now: 1450233040568 next: 1450233037583
I/CheckinService( 4203): active receiver: enabled
,I/CheckinService( 4203): Preparing to send checkin request
I/EventLogService( 4203): Accumulating logs since 1450233000741
V/DownloadManager( 3218): DownloadService onDestroy
,D/WeatherAncestor( 2775): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:30:40
,D/UpdateThreadPoolManager( 2775): 2 : This is isUpdating : false
D/WeatherAncestor( 2775): connectivity changed - connection : true
D/Weather_cast( 2775): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2775): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:30:40
D/WeatherService( 2775): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/CheckinRequestBuilder( 4203): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  974): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6921 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/ActivityThread( 4203): Failed to find provider info for com.google.android.wearable.settings
W/ActivityManager(  974): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2775): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2775): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2775): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6921): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  974): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6939 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6939): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6939): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel_SMS( 6921): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6921): MmsConfig.loadMmsSettings
V/AlarmManager(  974): RTC_WAKEUP set : Alarm{7a87054 type 0 when 1450233037583 com.google.android.gms} when 1450233037583
I/Babel_SMS( 6921): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6921): MmsConfig.loadFromDatabase
,I/ActivityManager(  974): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6968 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  974): RTC_WAKEUP set : Alarm{9e99bfd type 0 when 1450233041030 com.android.vending} when 1450233041030
,E/Babel_SMS( 6921): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6921): MmsConfig.loadFromResources
E/Babel_SMS( 6921): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6921): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/MultiDex( 6939): VM with version 2.1.0 has multidex support
I/MultiDex( 6939): install
I/MultiDex( 6939): VM has multidex support, MultiDex support library is disabled.
,D/SensorManager( 6921): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6921): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6921): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6921): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6921): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6921): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6921): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6921): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6921): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6921): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6921): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6921): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6921): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6921): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6921): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6921): found sensor: Motion Accel, handle=46
,I/art     ( 6921): CheckpointMarkThreadRoots callback created = 0xb042d810
,I/art     ( 6921): CheckpointMarkThreadRoots callback created = 0xb042d7e0
,I/art     (  974): Explicit concurrent mark sweep GC freed 15169(809KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.451ms total 158.645ms
,V/AlarmManager(  974): RTC_WAKEUP set : Alarm{283175ec type 0 when 1450233041292 com.google.android.googlequicksearchbox} when 1450233041292
V/JNIHelp ( 6939): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Settings( 6921): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6921): startup - clean
I/Babel   ( 6921): deleted: false for 0
,W/ActivityThread( 6939): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6939): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@25356ede: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6939): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6939): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6939): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 6939): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/Finsky  ( 6968): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/art     ( 6939): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,V/MusicLeanback( 6781): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
W/AudioCapabilities( 6921): Unsupported mime audio/x-lg-flac
,D/LGDMClient( 6836): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6836): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/AudioCapabilities( 6921): Unsupported mime audio/adpcm
W/ContextImpl( 6836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/AudioCapabilities( 6921): Unsupported mime audio/g726
W/AudioCapabilities( 6921): Unsupported mime audio/x-ms-wma
I/NetworkStateForAutoUpdateMonitor( 6861): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 6861): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6861): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6861): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6861): onReceive
I/AppUp4:CustModeStarterReceiver( 6861): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6861): Context : android.app.ReceiverRestrictedContext@2373a185
D/AppUp4:CustFacade( 6861): isCustomizationCompleted : false
W/AudioCapabilities( 6921): Unsupported mime audio/wma-voice
W/Settings( 6809): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppUp4:CustFacade( 6861): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6861): begin check event
I/AppUp4:CustModeStarterReceiver( 6861): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/LgeMiscReceiver( 3198): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3198): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3198): networkInfo.isConnected() = true
D/PhoneState( 3198): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 6880): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6880): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 3218): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3218): DownloadService onCreate
D/WeatherAncestor( 2775): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:30:41
W/VideoCapabilities( 6921): Unsupported mime video/mjpg
,D/UpdateThreadPoolManager( 2775): 2 : This is isUpdating : false
D/WeatherAncestor( 2775): connectivity changed - connection : true
D/Weather_cast( 2775): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2775): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:30:41
I/NotificationManager( 3218): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/WeatherService( 2775): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  974): getTasks: caller 10074 does not hold GET_TASKS; limiting output
I/DownloadManager( 3218): in removeSpuriousFiles
D/Weather.Utils( 2775): 2 : Utils getTopActivity com.lge.launcher2 / true
W/VideoCapabilities( 6921): Unsupported mime video/theora
D/WeatherService( 2775): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2775): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/LGDMClient( 6836): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
V/DownloadManager( 3218): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@19db4153 on behalf of 3218
V/DownloadManager( 3218): DownloadService onStartCommand
I/LGDMClient( 6836): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3218): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 6836): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6836): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@18894b8e on behalf of 3218
I/DownloadManager( 3218): in trimDatabase
V/DownloadManager( 3218): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/ContextImpl( 6836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6836): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6836): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6836): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6836): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/art     ( 6757): CheckpointMarkThreadRoots callback created = 0xb042dd90
D/LGDMClient( 6836): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@54e9faf on behalf of 3218
,I/art     ( 6757): CheckpointMarkThreadRoots callback created = 0xb042dd60
W/AudioCapabilities( 6921): Unsupported mime audio/evrc
,W/AudioCapabilities( 6921): Unsupported mime audio/qcelp
W/VideoCapabilities( 6921): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6921): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6921): Unsupported mime audio/qcelp
W/AudioCapabilities( 6921): Unsupported mime audio/evrc
,W/VideoCapabilities( 6921): Unsupported mime video/mp4v-esdp
D/NativeLibraryUtils( 6939): Install completed successfully. count=14 extracted=0
,I/VideoCapabilities( 6921): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6921): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6921): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6921): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6921): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  974): Process com.google.android.apps.magazines (pid 6666) has died
,V/DownloadManager( 3218): DownloadService onDestroy
I/vclib   ( 6921): onServiceConnected
W/Babel   ( 6921): Attempted to change video mute state without an active call.
D/libc-netbsd( 6921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,I/NotificationManager( 6921): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  270): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out( 6921): propertyValue:false
D/Finsky  ( 6968): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/ActivityManager(  974): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7024 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Babel   ( 6921): connection state changed from UNKNOWN to CONNECTED
W/Settings( 6968): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6968): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 6968): com.android.vending: cancel(-1050172287) by com.android.vending
,D/WVCdm   (  274): Instantiating CDM.
,I/WVCdm   (  274): CdmEngine::OpenSession
I/WVCdm   (  274): Level3 Library Dec 11 2014 16:13:16
V/DownloadManager( 3218): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/Ads     ( 6968): Skipping gmscore version check
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@37e8db45 on behalf of 6968
W/WVCdm   (  274): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  274): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  274): L1 library not specified. Falling Back to L3
D/Finsky  ( 6968): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6968): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 6968): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/WVCdm   (  274): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  274): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  274): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  274): CdmEngine::GenerateKeyRequest
D/WVCdm   (  274): PrepareKeyRequest: nonce=178092609
,D/Finsky  ( 6968): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7024): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7024): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7024):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7024):   adb logcat -s GAv4
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7024): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7024): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7024): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7024): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7024): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7024): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/Finsky  ( 6968): [865] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6968): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/art     ( 6939): CheckpointMarkThreadRoots callback created = 0xb042d960
,I/art     ( 6939): CheckpointMarkThreadRoots callback created = 0xb042d950
,I/WebViewFactory( 7024): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7024): Time to load native libraries: 2 ms (timestamps 2280-2282)
I/LibraryLoader( 7024): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7024): Binding Chromium to main looper Looper (main, tid 1) {18894b8e}
I/LibraryLoader( 7024): Expected native library version number "",actual native library version number ""
I/chromium( 7024): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7024): Initializing chromium process, singleProcess=true
W/art     ( 7024): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7024): ApplicationContext is null in ApplicationStatus
W/chromium( 7024): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7024): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7024): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7024): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7024): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7024): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7024): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7024): Remote Branch: 
I/Adreno-EGL( 7024): Local Patches: 
I/Adreno-EGL( 7024): Reconstruct Branch: 
V/AudioPolicyService(  274): registerClient() client 0xb3c3cd00, uid 10079
,W/AudioManagerAndroid( 7024): Requires BLUETOOTH permission
I/NSApplication( 7024): Starting up...
,I/ActivityManager(  974): Killing 6757:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  974): failed to open /acct/uid_10086/pid_6757/cgroup.procs: No such file or directory
,I/ActivityManager(  974): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7089 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  974): Killing 6781:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/dex2oat ( 7087): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
W/libprocessgroup(  974): failed to open /acct/uid_10081/pid_6781/cgroup.procs: No such file or directory
,W/ResourcesManager( 7089): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/dex2oat ( 7087): dex2oat took 103.452ms (threads: 4)
I/Adreno-EGL( 6939): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6939): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6939): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6939): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6939): Remote Branch: 
I/Adreno-EGL( 6939): Local Patches: 
I/Adreno-EGL( 6939): Reconstruct Branch: 
,I/ActivityManager(  974): Killing 6809:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  974): failed to open /acct/uid_10021/pid_6809/cgroup.procs: No such file or directory
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/WVCdm   (  274): CdmEngine::OpenSession
,I/ActivityManager(  974): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7120 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7120): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  974): Message: 20
D/BluetoothManagerService(  974): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39a3775:true
,D/BluetoothAdapterService(5506792)( 1968): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1bb597e
D/BluetoothAdapterService(5506792)( 1968): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1bb597e
I/ThermalEngine(  287): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  974): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7144 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7120): Create singleton instance
,D/UEI.SmartControl( 7144): Quickset Services start...
,I/UEI.SmartControl( 7144): Manufacture = LGE
D/UEI.SmartControl( 7144): File observer start...
E/UEI.SmartControl( 7144): IR Port is disabled: false
,D/UEI.SmartControl( 7144): Starting file observer...
D/UEI.SmartControl( 7144): Extracting JNI libs...
D/UEI.SmartControl( 7144): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7120): getMode name:com.lge.qremote
,I/CheckinService( 4203): Checkin interval check for package: unspecified last checkin: 1450233007619 min interval config: 0 actual interval: 36308
,D/WearableService( 1734): callingUid 10006, callindPid: 1734
,E/MDM     ( 1734): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4203): Restart initialization of location
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
I/AudioManager( 7120): getMode name:com.lge.qremote
,W/ContextImpl( 3611): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/UEI.SmartControl( 7144): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7144): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7144): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7144): --- Selecting new region: 2
I/UEI.SmartControl( 7144): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7144): Platform has CIR...
D/UEI.SmartControl( 7144): NO CIR support, need to check package...
I/UEI.SmartControl( 7144): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7144): QS Service created
E/UEI.SmartControl( 7144): QS start get config
,D/UEI.SmartControl( 7144): Loading JNI Libs...
,D/UEI.SmartControl( 7144):  configuring local db...
I/WVCdm   (  274): CdmEngine::CloseSession
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/WVCdm   (  274): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  274): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  274): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  274): CdmEngine::GenerateKeyRequest
D/WVCdm   (  274): PrepareKeyRequest: nonce=902946005
D/UEI.SmartControl( 7144):  ---- Has DB8: true
,D/UEI.SmartControl( 7144): QS start statue = true Error code = 0
D/UEI.SmartControl( 7144): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7144): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7144): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7144): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7144): IrrcClient ++ 
D/irrcClient( 7144): getIrrcService ++ 
D/irrcClient( 7144): getIrrcService -- 
D/irrcClient( 7144): IrrcClient -- 
W/irrc_jni( 7144): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7144): Services init done
,I/UEI.SmartControl( 7144): Device manager: loading config....
,D/UEI.SmartControl( 7144): QS Service init finished
D/UEI.SmartControl( 7144): QS Service version name: 0.1.73
D/UEI.SmartControl( 7144): QS Service version code: 1073
D/UEI.SmartControl( 7144): Service requested: Control
D/UEI.SmartControl( 7144): Config is loaded...
D/UEI.SmartControl( 7144):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7144): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7144): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7144): Internal service binding...
D/UEI.SmartControl( 7144): -----IControl: 11
D/UEI.SmartControl( 7144): Caller: com.lge.qremote
D/UEI.SmartControl( 7144): ------------ IControl registerCallback...
I/UEI.SmartControl( 7144): Registering callback...
D/UEI.SmartControl( 7144): -----IControl: 19
D/UEI.SmartControl( 7144): Caller: com.lge.qremote
I/UEI.SmartControl( 7144): Registering Services Ready callback...
I/UEI.SmartControl( 7144): Notify client services are ready...
D/UEI.SmartControl( 7144): -----IControl: 8
D/UEI.SmartControl( 7144): Caller: com.lge.qremote
I/AudioManager( 7120): getMode name:com.lge.qremote
,I/ActivityManager(  974): Killing 6902:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/ActivityManager(  974): Killing 6861:com.lge.appbox.client/u0a11 (adj 15): empty #12
,W/libprocessgroup(  974): failed to open /acct/uid_10051/pid_6902/cgroup.procs: No such file or directory
,W/libprocessgroup(  974): failed to open /acct/uid_10011/pid_6861/cgroup.procs: No such file or directory
I/AudioManager( 7120): getMode name:com.lge.qremote
I/AudioManager( 7120): getMode name:com.lge.qremote
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 114777254544; DSPS: 3859625; Offset : -3014654098
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WVCdm   (  274): CdmEngine::CloseSession
,I/WVCdm   (  274): L3 Terminate.
I/MusicWidget( 2720): mDelayedStopHandler : unbind
,I/MusicBrowser( 2792): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2792): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2792): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2792): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2792): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2792): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2792): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2792): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  974):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1ab859fbcom.lge.music.MediaPlaybackService$6@1f0afa18
,D/MusicBrowser( 2792): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@3d51d101
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2792): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2792): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2792): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2792): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2792): reset
V/MediaPlayer[Native]( 2792): setListener
V/MediaPlayer[Native]( 2792): disconnect
V/MediaPlayer[Native]( 2792): destructor
,V/AudioFlinger(  274): releasing 18 from 2792 for -1
V/AudioFlinger(  274):  decremented refcount to 0
V/AudioFlinger(  274): purging stale effects
V/MediaPlayer[Native]( 2792): disconnect
D/MusicBrowser( 2792): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2792): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2792): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2792): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2792): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2792): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2792): [SmartShareManagerClient] unregisterListener: 376437873
W/SmartShareClient( 2792): [SmartShareManagerClient] unregisterListener invalid listener: 376437873
I/SmartShareClient( 2792): [SmartShareManagerClient] terminate service: 2792/MediaPlaybackService/374598639
E/HomeCloudIF( 2792): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2792): [SmartShareManagerClient] unbindService context:android.app.Application@1cff1a56
V/CloudHub( 2792): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2792): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2792): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2792): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2792): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  974): Killing 6921:com.google.android.talk/u0a61 (adj 15): empty #11
I/CloudHub( 2792): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29987
,W/libprocessgroup(  974): failed to open /acct/uid_10061/pid_6921/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Adreno-EGL( 6939): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6939): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6939): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6939): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6939): Remote Branch: 
I/Adreno-EGL( 6939): Local Patches: 
I/Adreno-EGL( 6939): Reconstruct Branch: 
,I/Adreno-EGL( 6939): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6939): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6939): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6939): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6939): Remote Branch: 
I/Adreno-EGL( 6939): Local Patches: 
I/Adreno-EGL( 6939): Reconstruct Branch: 
,I/CheckinRequestBuilder( 4203): Classify the device as Phone.
,D/libc-netbsd( 4203): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4203): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4203): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4203): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  270): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
,I/System.out( 4203): propertyValue:false
D/libc-netbsd( 4203): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4203): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4203): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4203): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4203): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4203): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4203): Sending checkin request (9727 bytes)
,I/CheckinRequestBuilder( 4203): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4203): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 5563): Explicit concurrent mark sweep GC freed 2074(91KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.037ms total 34.802ms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4203): Classify the device as Phone.
,I/CheckinTask( 4203): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4203): Checking schedule, now: 1450233048558 next: 1450760297553
I/CheckinService( 4203): active receiver: disabled
,I/CheckinService( 4203): Checking schedule, now: 1450233048597 next: 1450760297553
,I/CheckinService( 4203): active receiver: disabled
D/CheckinService( 4203): Recording last checkin time for package unspecified as 1450233048605
V/SetupWizard( 6880): Connected to Gservices successfully
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ThermalEngine(  287): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  974): Killing 7024:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/ActivityManager(  974): Killing 6836:com.lge.lgdmsclient/1000 (adj 15): empty #12
,W/libprocessgroup(  974): failed to open /acct/uid_10079/pid_7024/cgroup.procs: No such file or directory
,W/libprocessgroup(  974): failed to open /acct/uid_1000/pid_6836/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7144): Internal timer expired: 1
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1376): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  974): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  974): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7234 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
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
,W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1376): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
W/ResourcesManager( 7234): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/administrator(  974): Handling package changes for user 0
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     (  974): Explicit concurrent mark sweep GC freed 28704(1345KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.859ms total 179.967ms
,I/Babel_SMS( 7234): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7234): MmsConfig.loadMmsSettings
I/Babel_SMS( 7234): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7234): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7234): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7234): MmsConfig.loadFromResources
E/Babel_SMS( 7234): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7234): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/NotificationService(  974): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  974): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  974): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  974): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  974): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  974): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@134c864
,D/SensorManager( 7234): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7234): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7234): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7234): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7234): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7234): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7234): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 7234): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7234): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7234): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7234): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7234): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7234): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7234): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7234): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7234): found sensor: Motion Accel, handle=46
W/ResourcesManager(  974): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/Settings( 7234): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7234): startup - clean
I/Babel   ( 7234): deleted: false for 0
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     ( 7234): CheckpointMarkThreadRoots callback created = 0xaaf408c0
,W/ResourceType(  974): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/art     ( 7234): CheckpointMarkThreadRoots callback created = 0xaaf40890
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,D/LocationProviderProxy(  974): applying state to connected service
,W/AudioCapabilities( 7234): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7234): Unsupported mime audio/adpcm
W/AudioCapabilities( 7234): Unsupported mime audio/g726
W/AudioCapabilities( 7234): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7234): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7234): Unsupported mime video/mjpg
W/VideoCapabilities( 7234): Unsupported mime video/theora
W/AudioCapabilities( 7234): Unsupported mime audio/evrc
,I/ActivityManager(  974): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7280 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/AudioCapabilities( 7234): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7234): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7234): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7234): Unsupported mime audio/qcelp
W/AudioCapabilities( 7234): Unsupported mime audio/evrc
,W/VideoCapabilities( 7234): Unsupported mime video/mp4v-esdp
,I/ActivityManager(  974): Process com.android.vending (pid 6968) has died
,I/VideoCapabilities( 7234): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7234): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7234): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7234): Unrecognized profile 2130706433 for video/avc
I/AppUp4:AppBoxCP( 7280): onCreate
W/AppUp4:DB( 7280):  [AppBoxDatabaseHelper] construct
W/VideoCapabilities( 7234): Unrecognized profile 2130706433 for video/avc
I/AppUp4:DB( 7280):  setFingerPrint start
I/AppUp4:DB( 7280):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7280):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7280):  SDK version = 0
I/AppUp4:DB( 7280):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7280): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7280): onReceive
I/AppUp4:CustModeStarterReceiver( 7280): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7280): Context : android.app.ReceiverRestrictedContext@6df20ce
D/AppUp4:CustFacade( 7280): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7280): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7280): begin check event
I/AppUp4:CustModeStarterReceiver( 7280): Event For Nothing, skip.
W/art     ( 7234): Suspending all threads took: 24.525ms
,I/ActivityManager(  974): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7301 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/art     (  337): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 333us total 22.454ms
,I/vclib   ( 7234): onServiceConnected
W/Babel   ( 7234): Attempted to change video mute state without an active call.
I/NotificationManager( 7234): com.google.android.talk: cancel(8) by com.google.android.talk
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.428ms
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.690ms
,W/ResourcesManager( 7234): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7234): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 7301): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7301): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7301): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/JNIHelp ( 7234): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppConfig( 7301): Total System Memory = 906309632
,I/GalleryUtils( 7301): Application Heap = 96 MB
I/AppConfig( 7301): App Tier : NOT_DEF
D/SystemHelper( 7301): region [EU], country [EU], operator [OPEN], sub-operator []
,W/System  ( 7234): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7234): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  974): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7322 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  974): Killing 6737:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  974): failed to open /acct/uid_10048/pid_6737/cgroup.procs: No such file or directory
,I/NotificationManager( 7234): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 7322): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7322): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7322): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7322): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7322): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7322): BUILD Country: EU
,I/SystemConfig( 7322): BUILD Operator: OPEN
I/ActivityManager(  974): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7348 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  974): Killing 7089:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  974): failed to open /acct/uid_10086/pid_7089/cgroup.procs: No such file or directory
,I/SystemConfig( 7322): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7322): existFile = false
I/SystemConfig( 7322): canReadFile = false
I/SystemConfig( 7322): systemFeature RCS result false
D/SystemConfig( 7322): refreshRcsSupport() :false
,I/LockScreenSettings( 7348): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7348): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7348): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7348): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7348): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7348): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  974): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7365 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  974): Killing 2792:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  274): 2792 died, releasing its sessions
V/AudioFlinger(  274):  pid 1752 @ 0
V/AudioFlinger(  274):  pid 3198 @ 1
V/AudioFlinger(  274):  pid 3198 @ 2
,W/libprocessgroup(  974): failed to open /acct/uid_10028/pid_2792/cgroup.procs: No such file or directory
,W/ResourcesManager( 7365): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1944): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  974): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7390 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  974): Killing 6880:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  974): failed to open /acct/uid_10038/pid_6880/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1944): UpdateCorporaTask done [took 112 ms] updated apps [took 112 ms] 
,D/Finsky  ( 7390): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7390): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7390): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7390): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7390): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 7390): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7390): [1] Libraries$2.run: Finished loading 1 libraries.
,V/DownloadManager( 3218): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@1d52929a on behalf of 7390
D/Ads     ( 7390): Skipping gmscore version check
,I/ActivityManager(  974): Killing 6939:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
D/Finsky  ( 7390): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/libprocessgroup(  974): failed to open /acct/uid_10006/pid_6939/cgroup.procs: No such file or directory
D/PackageBroadcastService( 4203): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4203): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7390): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4203): updateResources: need to parse f{com.google.android.gms}
I/ThermalEngine(  287): Sensor:pa_therm0:32000 mC
,I/Icing   ( 4203): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4203): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  974): Killing 7144:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7120): android.os.DeadObjectException
,W/libprocessgroup(  974): failed to open /acct/uid_10089/pid_7144/cgroup.procs: No such file or directory
W/ActivityManager(  974): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/System.err( 7120): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7120): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7120): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7120): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7120): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7120): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7120): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7120): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7120): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7120): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7120): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7120): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7120): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7120): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7120): IControl.unregisterCallback error: android.os.DeadObjectException
,W/System.err( 7120): android.os.DeadObjectException
W/System.err( 7120): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7120): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7120): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7120): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7120): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7120): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7120): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7120): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7120): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7120): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7120): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7120): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7120): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7120): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7120): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/ActivityManager(  974): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7485 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7485): Quickset Services start...
,I/UEI.SmartControl( 7485): Manufacture = LGE
D/UEI.SmartControl( 7485): File observer start...
E/UEI.SmartControl( 7485): IR Port is disabled: false
D/UEI.SmartControl( 7485): Starting file observer...
D/UEI.SmartControl( 7485): Extracting JNI libs...
D/UEI.SmartControl( 7485): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 7485): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7485): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7485): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7485): --- Selecting new region: 2
I/UEI.SmartControl( 7485): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7485): Platform has CIR...
,D/UEI.SmartControl( 7485): NO CIR support, need to check package...
I/UEI.SmartControl( 7485): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7485): QS Service created
E/UEI.SmartControl( 7485): QS start get config
,D/UEI.SmartControl( 7485): Loading JNI Libs...
,D/UEI.SmartControl( 7485):  configuring local db...
,D/charger_monitor(  489): init target 500000
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
,D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
,D/charger_monitor(  489): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
,D/UEI.SmartControl( 7485):  ---- Has DB8: true
,D/UEI.SmartControl( 7485): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7485): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 7485): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7485): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7485): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7485): IrrcClient ++ 
D/irrcClient( 7485): getIrrcService ++ 
,D/irrcClient( 7485): getIrrcService -- 
D/irrcClient( 7485): IrrcClient -- 
W/irrc_jni( 7485): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7485): Services init done
I/UEI.SmartControl( 7485): Device manager: loading config....
D/UEI.SmartControl( 7485): QS Service init finished
D/UEI.SmartControl( 7485): QS Service version name: 0.1.73
D/UEI.SmartControl( 7485): QS Service version code: 1073
D/UEI.SmartControl( 7485): Service requested: Control
D/UEI.SmartControl( 7485): Config is loaded...
,D/UEI.SmartControl( 7485):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7485): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7485): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7485): -----IControl: 11
I/ActivityManager(  974): Killing 7120:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7485): Caller: com.lge.qremote
D/UEI.SmartControl( 7485): ------------ IControl registerCallback...
I/UEI.SmartControl( 7485): Registering callback...
W/libprocessgroup(  974): failed to open /acct/uid_10106/pid_7120/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7485): Internal service binding...
I/ThermalEngine(  287): Sensor:pa_therm0:32000 mC
,D/PowerManagerServiceEx(  974): acquireWakeLockInternal: lock=139572392, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=974
,D/WeatherService( 2775): 2 : TimeTick Intent has been received, Time(hour:min:sec) 3:31:0
,D/WeatherService( 2775): 2 : TimeTick Intent And Screen On
D/WeatherService( 2775): 2 : SDK version : 21
W/ActivityManager(  974): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2775): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2775): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2775): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2775): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2775): 2 : This is isUpdating : false
D/WeatherService( 2775): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2775): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2775): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2775): 2 : Fixed theme : optimus
I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
,D/WeatherReflect( 2775): 2 : Map key string is -2
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/lim     ( 2775): 2 : time = 03:31
,I/WeatherReflect( 2775): Model Name : LG-D722
D/WeatherTheme( 2775): 2 : Different view - status_min_formatted : 30 != 31
D/WeatherTheme( 2775): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2775): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2775): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2775): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2775): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2775): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2775): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2775): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2775): forecast size is 0
D/Theme   ( 2775): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2775): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2775): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2775): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2775): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2775): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2775): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2775): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2775): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2775): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2775): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2775): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2775): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2775): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2775): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2775): url is : null
D/Theme   ( 2775): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2775): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2775): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2775): 2 : update view, appWidgetId: 2
,D/WeatherService( 2775): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 3:31:0
D/PowerManagerServiceEx(  974): releaseWakeLockInternal: lock=139572392 [*alarm*], flags=0x0
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7485): Internal timer expired: 1
,D/UEI.SmartControl( 7485): Service.onUnbind: IControl
D/UEI.SmartControl( 7485): Service.onDestroy
W/System.err( 7485): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@5406e8
W/System.err( 7485): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7485): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7485): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7485): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7485): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7485): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7485): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7485): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7485): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 7485): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7485): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7485): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7485): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7485): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7485): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7485): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@5406e8
D/UEI.SmartControl( 7485): Shutdown IRRCPlayer... 
W/irrc_jni( 7485): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7485): ~IrrcClient ++ 
D/irrcClient( 7485): ~IrrcClient -- 
W/irrc_jni( 7485): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7485): Blaster closed
D/UEI.SmartControl( 7485): Blaster closed
D/UEI.SmartControl( 7485): Shut down QS...
,D/UEI.SmartControl( 7485): Stopped file observer...
I/UEI.SmartControl( 7485): QS lib stop result = true
D/UEI.SmartControl( 7485): QS shutdown complete
I/ThermalEngine(  287): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 134778134797; DSPS: 4515014; Offset : -3014658958
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  287): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  974): ELAPSED_WAKEUP set : Alarm{11c54bc1 type 2 when 138477 com.google.android.gms} when 138477
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/VacuumService( 1734): Vacuum at: now=1450233069040 tag=VacuumService
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 38641(2MB) AllocSpace objects, 24(384KB) LOS objects, 39% free, 13MB/22MB, paused 1.358ms total 104.754ms
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  287): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  974): ALS enabled for SRE
,D/PowerManagerServiceEx(  974): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28325 ms ago)
D/qdlights(  974): set_light_backlight: 253
,D/qdlights(  974): set_light_backlight: 250
,D/qdlights(  974): set_light_backlight: 246
,I/ThermalEngine(  287): Sensor:pa_therm0:32000 mC
D/qdlights(  974): set_light_backlight: 243
,D/qdlights(  974): set_light_backlight: 240
,D/qdlights(  974): set_light_backlight: 236
,D/qdlights(  974): set_light_backlight: 233
,D/qdlights(  974): set_light_backlight: 230
,D/qdlights(  974): set_light_backlight: 226
,D/qdlights(  974): set_light_backlight: 223
,D/qdlights(  974): set_light_backlight: 220
,D/qdlights(  974): set_light_backlight: 216
,D/qdlights(  974): set_light_backlight: 213
,D/qdlights(  974): set_light_backlight: 210
,D/qdlights(  974): set_light_backlight: 206
,D/qdlights(  974): set_light_backlight: 203
,D/qdlights(  974): set_light_backlight: 200
,D/qdlights(  974): set_light_backlight: 196
,D/qdlights(  974): set_light_backlight: 193
,D/qdlights(  974): set_light_backlight: 190
,D/qdlights(  974): set_light_backlight: 186
,D/qdlights(  974): set_light_backlight: 183
,D/qdlights(  974): set_light_backlight: 180
,D/qdlights(  974): set_light_backlight: 176
,D/qdlights(  974): set_light_backlight: 173
,D/qdlights(  974): set_light_backlight: 170
,D/qdlights(  974): set_light_backlight: 166
,D/qdlights(  974): set_light_backlight: 163
,D/qdlights(  974): set_light_backlight: 160
,D/qdlights(  974): set_light_backlight: 156
,D/qdlights(  974): set_light_backlight: 153
,D/qdlights(  974): set_light_backlight: 150
,D/qdlights(  974): set_light_backlight: 146
,D/qdlights(  974): set_light_backlight: 143
,D/qdlights(  974): set_light_backlight: 140
,D/qdlights(  974): set_light_backlight: 136
,D/qdlights(  974): set_light_backlight: 133
,D/qdlights(  974): set_light_backlight: 130
,D/qdlights(  974): set_light_backlight: 126
,D/qdlights(  974): set_light_backlight: 123
,D/qdlights(  974): set_light_backlight: 120
,D/qdlights(  974): set_light_backlight: 116
,D/qdlights(  974): set_light_backlight: 113
,D/qdlights(  974): set_light_backlight: 110
,D/qdlights(  974): set_light_backlight: 106
,D/qdlights(  974): set_light_backlight: 103
,D/qdlights(  974): set_light_backlight: 100
,D/qdlights(  974): set_light_backlight: 96
,D/qdlights(  974): set_light_backlight: 93
,D/qdlights(  974): set_light_backlight: 90
,D/qdlights(  974): set_light_backlight: 86
,D/qdlights(  974): set_light_backlight: 83
,D/qdlights(  974): set_light_backlight: 80
,D/qdlights(  974): set_light_backlight: 76
,D/qdlights(  974): set_light_backlight: 73
,D/qdlights(  974): set_light_backlight: 70
,D/qdlights(  974): set_light_backlight: 66
,D/qdlights(  974): set_light_backlight: 63
,D/qdlights(  974): set_light_backlight: 60
,D/qdlights(  974): set_light_backlight: 56
,D/qdlights(  974): set_light_backlight: 53
,D/qdlights(  974): set_light_backlight: 50
,D/qdlights(  974): set_light_backlight: 46
,D/qdlights(  974): set_light_backlight: 43
,D/qdlights(  974): set_light_backlight: 40
,D/qdlights(  974): set_light_backlight: 36
,D/qdlights(  974): set_light_backlight: 33
,D/qdlights(  974): set_light_backlight: 30
,D/qdlights(  974): set_light_backlight: 26
,D/qdlights(  974): set_light_backlight: 23
,D/qdlights(  974): set_light_backlight: 20
,D/qdlights(  974): set_light_backlight: 16
,D/qdlights(  974): set_light_backlight: 13
,D/qdlights(  974): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  287): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 154778909320; DSPS: 5170399; Offset : -3014647608
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  974): ALS enabled for SRE
D/PowerManagerServiceEx(  974): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35318 ms ago)
I/PowerManagerService(  974): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  974): ALS enabled for SRE
D/PowerManagerServiceEx(  974): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35329 ms ago)
W/ContextImpl(  974): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  974): Sleeping (uid 1000)...
D/LPWGController(  974): [updateScreenState] screen on = false
D/LPWGController(  974): disable proximity sensor
D/LPWGController(  974): enable proximity sensor
,I/SensorManager(  974): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2f49d53e] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  974): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
,D/sensors_hal_SAM(  974): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  974): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  974): activate: handle is 48, enable
V/sensors_hal_Ctx(  974): activate sensors is 1400000000000
D/sensors_hal_Thresh(  974): enable: handle=48
I/sensors_hal_SAM(  974): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  974): waitForResponse: timeout=1000
V/sensors_hal_SAM(  974): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  974): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  974): enable: Received response: 0
D/PowerManagerServiceEx(  974): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35370 ms ago)
I/Adreno-EGL(  974): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  974): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  974): Build Date: 03/02/15 Mon
I/Adreno-EGL(  974): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  974): Remote Branch: 
I/Adreno-EGL(  974): Local Patches: 
I/Adreno-EGL(  974): Reconstruct Branch: 
,D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1031 us)
,I/Sensors (  425): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  974): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  974): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  974): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  974): processInd: handle 48, count=1
V/sensors_hal_Thresh(  974): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  974): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  974): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  974): poll: count: 256
I/sensors_hal_Ctx(  974): poll: released wakelock sensor_ind
D/sensors_hal_Util(  974): waitForResponse: timeout=0
D/LPWGController(  974): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  974): current mode = 1  value = 1 1
I/LPWGController(  974): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  974): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdlights(  974): set_light_backlight: 0
,I/SensorManager(  974): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  974): activate: handle is 46, disable
V/sensors_hal_Ctx(  974): activate sensors is 1000000000000
D/sensors_hal_LP2(  974): enable: handle=46
D/sensors_hal_LP2(  974): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  974): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
I/DisplayManagerService(  974): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  974): Display changed displayId=0
,V/sensors_hal_SAM(  974): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  974): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1752): Display #0 changed.
,D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
D/SurfaceControl(  974): Excessive delay in setPowerMode(): 211ms
I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  974): Got set_interactive hint
D/KeyguardViewMediator( 1376): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1335): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1335): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1335): handleNotifyScreenOFF
D/KeyguardViewMediator( 1376): notifyScreenOffLocked
,D/KeyguardViewMediator( 1376): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1376): handleNotifyScreenOff
D/WifiServerServiceExt(  974): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  274): setParameters(): io 0, keyvalue screen_state=on, calling pid 974
D/audio_hw_primary(  274): adev_set_parameters: enter: screen_state=on
V/voice   (  274): voice_set_parameters: enter: screen_state=on
V/compress_voip(  274): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  274): voice_extn_compress_voip_set_parameters: exit
V/voice   (  274): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  274): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  274): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  274): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  274): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  274): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  274): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  274): adev_set_parameters: exit with code(0)
,D/ScreenTurnOffBySensor( 1376): unregisterProximitySensor
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/StatusBarWindowView( 1376): onScreenTurnedOff why = 3
I/WifiServerServiceExt(  974): set CMD_KT_SCAN_INTERVAL
,D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
,D/GpsLocationProvider(  974): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
I/LEDService( 1796): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1796): stopPatternFlashing()
I/Cliptray Service( 1796): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1796): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1796): lockStatus = 0
I/LEDService( 1796): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1796): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
I/LEDService( 1796): updateLightsLocked : turn off led
D/qdlights( 1796): set_light_notifications: 0,0,0,0,3
,D/LEDHandler( 1796): RESTART MSG
D/NfcServiceNXP( 1786): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1786): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 3
D/NfcService( 1786): Discovery configuration equal, not updating.
D/SplitWindow(  974): check instance of lgWin Window{2e1774b5 u0 SearchPanel}
,D/Ulp_jni (  974): JNI:system_update. Event-0
,D/InputDispatcher(  974): Window went away: Window{10025d4f u0 SearchPanel}
I/[SystemUI]Clock( 1376): onReceive = android.intent.action.SCREEN_ON
,I/Sensors (  425): sns_pwr.c(301):releasing wakelock
I/LgeClockWidgetControlView( 1376): time changed, timezoneChanged : false
,V/PhoneApp( 1752): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2775): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:31:27
,D/WeatherService( 2775): 2 : ACTION screen on
D/WeatherService( 2775): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2775): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2775): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:31:27
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): ACTION_SCREEN_ON
,D/AppCleanupService( 4058): android.intent.action.SCREEN_ON
V/AudioFlinger(  274): setParameters(): io 0, keyvalue screen_state=off, calling pid 974
,D/audio_hw_primary(  274): adev_set_parameters: enter: screen_state=off
V/voice   (  274): voice_set_parameters: enter: screen_state=off
V/compress_voip(  274): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  274): voice_extn_compress_voip_set_parameters: exit
V/voice   (  274): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  274): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  274): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  274): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  274): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  274): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  274): adev_set_parameters: exit with code(0)
D/WifiController(  974): CMD_SCREEN_OFF 
D/WifiController(  974): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  974): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1796): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1796): stopPatternFlashing()
D/qdlights( 1796): set_light_notifications: 0,0,0,0,3
I/LEDService( 1796): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1796): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1796): clear
I/LEDService( 1796): updateLightsLocked : turn on led
E/LEDService( 1796): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1796): Can't handle this request of patternId:0
D/LEDHandler( 1796): RESTART MSG
I/Cliptray Service( 1796): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1752): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2775): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:31:27
D/WeatherService( 2775): 2 : ACTION screen off
D/WeatherService( 2775): 2 : TimeTick Receiver Unregister
D/WeatherService( 2775): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:31:27
,W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  974): ACTION_SCREEN_OFF
D/AppCleanupService( 4058): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4058): AppUsageStatsSaveTask
,E/NxpNfcJni( 1786): getReconnectState = 0x0
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: 0
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 1
E/NxpNfcJni( 1786): getReconnectState = 0x0
,I/ThermalEngine(  287): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1376): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  974): ELAPSED_WAKEUP set : Alarm{3e8a074a type 2 when 161254 com.android.systemui} when 161254
,D/PhoneUtils( 1752): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1752): getCallState : 0
D/PhoneUtils( 1752): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
,D/KeyguardUpdateMonitor( 1376): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1376): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  287): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 174779582229; DSPS: 5825782; Offset : -3014676292
,I/ThermalEngine(  287): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1734): disconnect managed GoogleApiClient
,D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
V/AlarmManager(  974): ELAPSED_WAKEUP set : Alarm{1c39d6bb type 2 when 187289 com.google.android.gms} when 187289
,D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  974): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
,I/art     (  974): Explicit concurrent mark sweep GC freed 56397(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.281ms total 175.934ms
,I/PhenotypeConfigurator( 1734): Scheduling Phenotype for one-off execution 14299 seconds from now (1450233118116)
,D/GetConfigurationSnapshotOperation( 1734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  974): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  270): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  270): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
,D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
,I/System.out( 1734): propertyValue:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  287): Sensor:pa_therm0:31000 mC
,D/LocationManagerService(  974): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/AlarmManager(  974): ELAPSED_WAKEUP set : Alarm{297d89f0 type 2 when 188737 android} when 188737
,D/LocationManagerService(  974): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  974): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  974): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  974): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 194780619357; DSPS: 6481175; Offset : -3014646869
,I/ThermalEngine(  287): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 214781331225; DSPS: 7136559; Offset : -3014666720
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 234782086998; DSPS: 7791944; Offset : -3014673756
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 254782842459; DSPS: 8447328; Offset : -3014651107
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 274783519587; DSPS: 9102710; Offset : -3014645158
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 294784360830; DSPS: 9758098; Offset : -3014658667
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 314785034989; DSPS: 10413480; Offset : -3014655948
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6172): Connected to the server!
I/jxcore-log( 6172): 
,I/chromium( 6172): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 334790245971; DSPS: 11069011; Offset : -3014663497
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/LocationManagerService(  974): remove 119975d3
D/LocationManagerService(  974): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  974): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  974): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  974): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  974): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  974): acquireWakeLockInternal: lock=139572392, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=974
,D/PowerManagerServiceEx(  974): releaseWakeLockInternal: lock=139572392 [*alarm*], flags=0x0
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 354790914036; DSPS: 11724393; Offset : -3014666897
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  974): battery changed pluggedType: 2
I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 374791686477; DSPS: 12379778; Offset : -3014657317
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 394792394906; DSPS: 13035161; Offset : -3014650532
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 414793178961; DSPS: 13690547; Offset : -3014659777
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 434793999891; DSPS: 14345934; Offset : -3014663083
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 454794637956; DSPS: 15001315; Offset : -3014666330
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 474795286855; DSPS: 15656696; Offset : -3014658039
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 494795971535; DSPS: 16312079; Offset : -3014675446
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 514796732933; DSPS: 16967463; Offset : -3014646392
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 534797385426; DSPS: 17622845; Offset : -3014665311
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  974): battery changed pluggedType: 2
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 554798056355; DSPS: 18278227; Offset : -3014665899
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 574798895774; DSPS: 18933614; Offset : -3014650273
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 594799551496; DSPS: 19588996; Offset : -3014665886
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 614800518312; DSPS: 20244388; Offset : -3014675632
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 634801255751; DSPS: 20899772; Offset : -3014670485
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  974): acquireWakeLockInternal: lock=139572392, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=974
,V/AlarmManager(  974): RTC_WAKEUP set : Alarm{25a4a708 type 0 when 1450233579696 com.google.android.gms} when 1450233579696
D/PowerManagerServiceEx(  974): releaseWakeLockInternal: lock=139572392 [*alarm*], flags=0x0
,I/EventLogService( 4203): Aggregate from 1450233040626 (log), 1450231779568 (data)
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 654802002099; DSPS: 21555156; Offset : -3014656481
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 674802695841; DSPS: 22210539; Offset : -3014664590
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 694803348229; DSPS: 22865920; Offset : -3014653333
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 714804086555; DSPS: 23521304; Offset : -3014647141
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 734804759568; DSPS: 24176687; Offset : -3014676059
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 754805489613; DSPS: 24832070; Offset : -3014648569
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 774806245750; DSPS: 25487455; Offset : -3014655059
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 794807088607; DSPS: 26142843; Offset : -3014666435
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 814807907350; DSPS: 26798230; Offset : -3014672134
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 834808552082; DSPS: 27453611; Offset : -3014667412
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 854809226553; DSPS: 28108993; Offset : -3014664510
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 874810476598; DSPS: 28764394; Offset : -3014665556
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 894811208465; DSPS: 29419778; Offset : -3014666788
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 914811875125; DSPS: 30075160; Offset : -3014671410
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 934812625013; DSPS: 30730544; Offset : -3014653241
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  974): acquireWakeLockInternal: lock=139572392, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=974
,V/AlarmManager(  974): ELAPSED_WAKEUP set : Alarm{38e8a3dd type 2 when 952116 com.android.bluetooth} when 952116
D/PowerManagerServiceEx(  974): releaseWakeLockInternal: lock=139572392 [*alarm*], flags=0x0
,W/bt-smp  ( 1968): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1968): Plain text(LSB ~ MSB) = 6e 95 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 1968): Encrypted text(LSB ~ MSB) = 71 56 c5 d5 3d 49 ed 15 04 d5 7f 1c 23 97 37 50 
W/bt-btm  ( 1968): Stopping oneshot timer
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 954813275265; DSPS: 31385926; Offset : -3014674636
,V/AlarmManager(  974): ELAPSED_WAKEUP set : Alarm{36e94b52 type 2 when 956651 android} when 956651
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
,I/[SystemUI]Clock( 1376): called onTimeUpdated()
I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 974813943591; DSPS: 32041307; Offset : -3014647205
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 994814644208; DSPS: 32696690; Offset : -3014648674
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  974): acquireWakeLockInternal: lock=139572392, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=974
,V/AlarmManager(  974): ELAPSED_WAKEUP set : Alarm{9b43e23 type 2 when 1003349 com.google.android.gms} when 1003349
I/art     (  337): Background concurrent mark sweep GC freed 787(33KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 6.602ms total 47.323ms
,I/ActivityManager(  974): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7754 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 7754): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7754): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@6df20ce
,D/PowerManagerServiceEx(  974): releaseWakeLockInternal: lock=139572392 [*alarm*], flags=0x0
I/ActivityManager(  974): Killing 7280:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  974): failed to open /acct/uid_10011/pid_7280/cgroup.procs: No such file or directory
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1014815499826; DSPS: 33352078; Offset : -3014647576
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1034816240599; DSPS: 34007463; Offset : -3014669690
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1054816881946; DSPS: 34662844; Offset : -3014669628
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1074817619178; DSPS: 35318228; Offset : -3014664532
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1094818500212; DSPS: 35973616; Offset : -3014637807
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1114819155985; DSPS: 36628998; Offset : -3014653447
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1134819975717; DSPS: 37284385; Offset : -3014657404
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1154830912273; DSPS: 37940104; Offset : -3014677231
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1174831570494; DSPS: 38595485; Offset : -3014659723
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1194832323872; DSPS: 39250870; Offset : -3014669154
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  974): battery changed pluggedType: 2
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1214833177406; DSPS: 39906258; Offset : -3014670139
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  974): User[0] Flushing usage stats to disk
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1234833874638; DSPS: 40561641; Offset : -3014674784
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1254834518120; DSPS: 41217022; Offset : -3014672380
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1274835287174; DSPS: 41872407; Offset : -3014666318
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1294836046177; DSPS: 42527792; Offset : -3014670358
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1314836842732; DSPS: 43183178; Offset : -3014666895
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1334837538922; DSPS: 43838561; Offset : -3014672454
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1354838179383; DSPS: 44493942; Offset : -3014673435
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1374838835938; DSPS: 45149323; Offset : -3014657332
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
,I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1394839587597; DSPS: 45804708; Offset : -3014668612
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1414840444413; DSPS: 46460096; Offset : -3014666472
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1434841105864; DSPS: 47115478; Offset : -3014676276
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1454841864398; DSPS: 47770862; Offset : -3014650581
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1474842611317; DSPS: 48426247; Offset : -3014666732
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1494843357090; DSPS: 49081631; Offset : -3014652730
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1514844114427; DSPS: 49737016; Offset : -3014658488
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1534844850565; DSPS: 50392400; Offset : -3014654695
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1554845564828; DSPS: 51047784; Offset : -3014673140
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1574846246279; DSPS: 51703166; Offset : -3014663127
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1594846980073; DSPS: 52358550; Offset : -3014661313
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1614847770430; DSPS: 53013936; Offset : -3014664203
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  974): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  974): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  974): battery changed pluggedType: 2
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1634848482037; DSPS: 53669319; Offset : -3014654788
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1654849286925; DSPS: 54324706; Offset : -3014674083
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1674849946345; DSPS: 54980087; Offset : -3014655323
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1694850892119; DSPS: 55635478; Offset : -3014655985
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1714851539819; DSPS: 56290859; Offset : -3014648685
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1734852191739; DSPS: 56946241; Offset : -3014668230
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1754852959127; DSPS: 57601626; Offset : -3014664303
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1774853798286; DSPS: 58257013; Offset : -3014648909
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1794854461716; DSPS: 58912395; Offset : -3014656893
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
,I/[SystemUI]Clock( 1376): called onTimeUpdated()
I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1814855334208; DSPS: 59567784; Offset : -3014669776
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1834855998628; DSPS: 60223166; Offset : -3014676038
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  974): acquireWakeLockInternal: lock=139572392, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=974
,V/AlarmManager(  974): ELAPSED_WAKEUP set : Alarm{1450a0d9 type 2 when 1852248 com.android.bluetooth} when 1852248
,W/bt-smp  ( 1968): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1968): Plain text(LSB ~ MSB) = bc f7 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1968): Encrypted text(LSB ~ MSB) = ef 50 7d 03 6a f2 30 e2 5d cc 72 39 dc b4 7e a6 
W/bt-btm  ( 1968): Stopping oneshot timer
I/ProcessStatsService(  974): Prepared write state in 15ms
,D/PowerManagerServiceEx(  974): releaseWakeLockInternal: lock=139572392 [*alarm*], flags=0x0
,I/ProcessStatsService(  974): Prepared write state in 16ms
,I/ProcessStatsService(  974): Pruning old procstats: /data/system/procstats/state-2015-12-15-16-15-03.bin
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1854856663672; DSPS: 60878547; Offset : -3014651864
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  287): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1874857430122; DSPS: 61533932; Offset : -3014648483
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  974): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  974): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  974): tsOffsetIs: Apps: 1894858095115; DSPS: 62189314; Offset : -3014654774
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  974): acquireWakeLockInternal: lock=139572392, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=974
,V/AlarmManager(  974): ELAPSED_WAKEUP set : Alarm{382cca9e type 2 when 1903524 com.google.android.gms} when 1903524
,I/DigitalAppWidgetProvider( 7754): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7754): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@6df20ce
,TIME-OUT KILL (timeout was 1800000ms),D/PowerManagerServiceEx(  974): releaseWakeLockInternal: lock=139572392 [*alarm*], flags=0x0
D/AndroidRuntime( 7917): 
D/AndroidRuntime( 7917): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7917): CheckJNI is OFF
D/AndroidRuntime( 7917): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  974): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  974): Killing 6172:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  974): WIN DEATH: Window{284f4730 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  974): Focus left window: Window{284f4730 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  974): Window went away: Window{284f4730 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  974): Skipping PackageSetting{8226b29 com.example.hello/10317} due to missing metadata
I/ActivityManager(  974):   Force finishing activity ActivityRecord{1dcef3ed u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  974): Display changed displayId=0
D/DSDPConnection( 1752): Display #0 changed.
I/ThermalEngine(  287): Sensor:pa_therm0:28000 mC
W/ActivityManager(  974): Spurious death for ProcessRecord{2502997f 6172:com.test.thalitest/u0a316}, curProc for 6172: null
I/ActivityManager(  974): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  974):   Force finishing activity ActivityRecord{1dcef3ed u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  974): Duplicate finish request for ActivityRecord{1dcef3ed u0 com.test.thalitest/.MainActivity t220 f}
D/KeyguardModel( 1376): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader(  974): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1734): Ignoring removeGeofence because network location is disabled.
W/System.err( 3611): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3611): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3611): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3611): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3611): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3611): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3611): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3611): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3611): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3611): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3611): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3611): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  974): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7950 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
I/art     ( 1944): Explicit concurrent mark sweep GC freed 8899(568KB) AllocSpace objects, 3(72KB) LOS objects, 39% free, 11MB/19MB, paused 1.453ms total 118.264ms
I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
I/[LGHome]EVENT( 1878): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
D/KeyguardModel( 1376): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1376): createShortcutInfo...
I/[SystemUI]QSlideListController( 1376): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1376): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1376): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
I/Activity( 1878): Activity.onPostResume() called 
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
W/ResourcesManager( 1376): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1376): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1376): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1376): createShortcutInfo...
I/art     ( 4203): Explicit concurrent mark sweep GC freed 13668(807KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 14MB/18MB, paused 943us total 204.454ms
W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 1376): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/SystemUI[Framework](  974): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/InputDispatcher(  974): Focus entered window: Window{2a8553d4 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  974): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  974): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  974): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  974): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@30e8a2ef,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  974): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  974): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  974): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  974): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  974): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  974): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@30e8a2ef,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  974): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1376): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1376): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1376): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1376): createShortcutInfo...
W/ResourcesManager( 1376): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1376): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1376): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/art     (  974): Explicit concurrent mark sweep GC freed 45005(2MB) AllocSpace objects, 10(318KB) LOS objects, 33% free, 23MB/35MB, paused 7.289ms total 261.539ms
I/art     (  974): WaitForGcToComplete blocked for 175.481ms for cause Explicit
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourcesManager( 7950): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7950): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7950): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1376): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1376): createShortcutInfo...
D/KeyguardModel( 1376): handleShortcutListChanged...
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/KeyguardModel( 1376): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1376): createShortcutInfo...
I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1376): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1376): createShortcutInfo...
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1376): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1376): createShortcutInfo...
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1376): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1376): createShortcutInfo...
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1376): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1376): createShortcutInfo...
D/KeyguardModel( 1376): handleShortcutListChanged...
D/administrator(  974): Handling package changes for user 0
I/LGEmail ( 7950): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7950): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
W/InputMethodManagerService(  974): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  974): Got RemoteException sending setActive(false) notification to pid 6172 uid 10316
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  974): Timeline: Activity_windows_visible id: ActivityRecord{3572d9c6 u0 com.lge.launcher2/.Launcher t219} time:1905651
I/art     (  974): Explicit concurrent mark sweep GC freed 6543(376KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 10.335ms total 316.349ms
W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1587): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1878): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/PackageChangeReceiver( 7950): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/NotificationService(  974): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  974): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
D/JobSchedulerService(  974): Receieved: android.intent.action.PACKAGE_REMOVED
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
D/AndroidRuntime( 7917): Shutting down VM
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
I/ActivityManager(  974): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7979 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  974): Killing 7234:com.google.android.talk/u0a61 (adj 15): empty #11
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
D/PhoneStatusBar( 1376): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1376): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1376): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1376):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1376): , Keyguard show=false, IME shown=false, Panel expanded=false
W/libprocessgroup(  974): failed to open /acct/uid_10061/pid_7234/cgroup.procs: No such file or directory
D/TaskPersister(  974): removeObsoleteFile: deleting file=220_task.xml
I/AppUp4:AppBoxCP( 7979): onCreate
W/AppUp4:DB( 7979):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7979):  setFingerPrint start
I/AppUp4:DB( 7979):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7979):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7979):  SDK version = 0
I/AppUp4:DB( 7979):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7979): AppBoxApplication onCreate()
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
D/AppUp4:PreloadHelper( 7979): added Exclude : com.test.thalitest
W/ResourcesManager(  974): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  974): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7996 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  974): Killing 7301:com.android.gallery3d/u0a23 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
W/libprocessgroup(  974): failed to open /acct/uid_10023/pid_7301/cgroup.procs: No such file or directory
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourceType(  974): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/ResourcesManager( 7996): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7996): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7996): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7996): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/ResourcesManager( 7996): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline( 1878): Timeline: Activity_idle id: android.os.BinderProxy@1944d64a time:1906238
E/SharedPreferencesImpl( 1878): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
E/SQLiteDatabase( 7996): Failed to open database '/data/data/com.android.settings/databases/vibrateuserpattern.db'.
E/SQLiteDatabase( 7996): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7996): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 7996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 7996): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 7996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 7996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7996): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 7996): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 7996): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 7996): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 7996): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7996): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7996): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7996): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/SQLiteDatabase( 7996): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 7996): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 7996): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 7996): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 7996): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 7996): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 7996): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7996): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7996): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7996): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 7996): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7996): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7996): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 7996): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/AndroidRuntime( 7996): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 7996): FATAL EXCEPTION: main
E/AndroidRuntime( 7996): Process: com.android.settings, PID: 7996
E/AndroidRuntime( 7996): java.lang.RuntimeException: Unable to get provider com.android.settings.vibratecreation.VibrateUserPatternProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7996): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 7996): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 7996): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 7996): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 7996): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7996): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7996): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7996): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 7996): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7996): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7996): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 7996): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 7996): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7996): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 7996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 7996): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 7996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 7996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7996): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 7996): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 7996): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 7996): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 7996): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7996): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7996): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7996): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/AndroidRuntime( 7996): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 7996): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 7996): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 7996): 	... 11 more
I/Process ( 7996): Sending signal. PID: 7996 SIG: 9
I/art     ( 1878): Explicit concurrent mark sweep GC freed 26007(1428KB) AllocSpace objects, 18(2MB) LOS objects, 40% free, 15MB/25MB, paused 899us total 48.258ms
E/DropBoxManagerService(  974): Can't write: system_app_crash
E/DropBoxManagerService(  974): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  974): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  974): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  974): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  974): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  974): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  974): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
E/DropBoxManagerService(  974): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  974): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  974): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  974): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  974): 	... 5 more
I/ActivityManager(  974): Process com.android.settings (pid 7996) has died

```
