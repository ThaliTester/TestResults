#### Test 56151093f6e24ff_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  839): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6357 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
--------- beginning of main
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
W/ResourcesManager( 6357): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6357): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6357): VM with version 2.1.0 has multidex support
I/MultiDex( 6357): install
I/MultiDex( 6357): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6357): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 6357): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6357): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39b02799: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6357): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6357): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6357): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1731): callingUid 10006, callindPid: 1731
E/MDM     ( 1731): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4240): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
I/art     ( 5705): Explicit concurrent mark sweep GC freed 8168(408KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 455us total 60.572ms
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
I/qtaguid ( 6249): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6249): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6249): untagSocket(41) failed with errno -22
I/art     (  839): Explicit concurrent mark sweep GC freed 27525(1349KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.643ms total 169.520ms
D/ChimeraCfgMgr( 6357): Reading stored module config
D/AndroidRuntime( 6381): 
D/AndroidRuntime( 6381): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6381): CheckJNI is OFF
D/ChimeraCfgMgr( 6357): Loading module com.google.android.gms.car from APK com.google.android.gms
I/art     ( 6249): CheckpointMarkThreadRoots callback created = 0xb0581360
D/AlertService( 6065): Beginning updateAlertNotification
D/AlertService( 6065): No fired or scheduled alerts
I/NotificationManager( 6065): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(2) by com.android.calendar
I/art     ( 6249): CheckpointMarkThreadRoots callback created = 0xb0581320
I/NotificationManager( 6065): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6065): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6065): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 6065): No events found starting within 1 week.
D/NativeLibraryUtils( 6357): Install completed successfully. count=14 extracted=0
D/CAR.SERVICE( 6357): Connecting to CarCallService...
I/art     ( 6357): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6357): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 6357): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 6357): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6357): Creating a new PhoneAdapter instance
W/ActivityManager(  839): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6357): setListener: com.google.android.gms.car.dn@28c9c73c
W/ActivityManager(  839): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6357): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6357): Starting CarCallService with initial phone null
I/NotificationManager( 6357): com.google.android.gms: cancel(10436) by com.google.android.gms
D/AndroidRuntime( 6381): Calling main entry com.android.commands.am.Am
I/ActivityManager(  839): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/CAR.SERVICE( 6357): Package validated; name: com.android.vending
D/ActivityManager(  839): setTaskToReturnTo : TaskRecord{ada344b #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  839): setTaskToReturnTo : TaskRecord{ada344b #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  839): AppWindowTokenEx init.. 
D/ContextHelper(  839): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  839): Focus left window: Window{36a42b18 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6381): Shutting down VM
D/SplitWindow(  839): check instance of lgWin Window{3995767d u0 Starting com.test.thalitest}
I/ActivityManager(  839): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6418 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 420us total 30.994ms
I/NotificationManager( 6249): com.android.vending: cancel(10436) by com.android.vending
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 399us total 26.193ms
V/Finsky  ( 6249): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 407us total 29.013ms
I/WindowStateAnimator(  839): Starting window displayed
I/HotwordDetector( 1941): Closing mic
I/SystemUI[Framework](  839): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx(  839): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  839): setLGSystemUiVisibility(0x0)
,D/StatusBarManagerServiceEx(  839): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@204dda43,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BarTransitions( 1370): draw background and invalidate : color = 15000000
D/BarTransitions( 1370): draw background and invalidate : color = 14131313
I/MicrophoneInputStream( 1941): mic_close com.google.android.apps.gsa.speech.audio.u@182f6294
V/AudioRecord( 1941): stop()
D/AudioRecord( 1941): AudioRecord->stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
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
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb39e7000
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
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
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb39e7000
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioPolicyManager(  283): releaseInput() 17
V/AudioPolicyManager(  283): closeInput(17)
V/AudioFlinger(  283): closeInput() 17
V/AudioSystem(  283): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  839): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): ThreadBase::exit
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): RecordThread 0xb39e7000 exiting
V/AudioSystem( 2026): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2689): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1941): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  283): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  283): releaseInput() exit
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioFlinger(  283): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioFlinger(  283): removeClient_l() pid 1941, calling pid 283
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioSystem( 3155): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): releasing 16 from 1941 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
I/HotwordRecognitionRnr( 1941): Stopping hotword detection.
I/HotwordRecognitionRnr( 1941): Hotword detection finished
D/ContextHelper( 6418): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/ActivityManager(  839): Killing 6065:com.android.calendar/u0a13 (adj 15): empty #11
I/WebViewFactory( 6418): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/libprocessgroup(  839): failed to open /acct/uid_10013/pid_6065/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LibraryLoader( 6418): Time to load native libraries: 2 ms (timestamps 6589-6591)
I/LibraryLoader( 6418): Expected native library version number "",actual native library version number ""
I/NotificationManager(  839): android: cancelAsUser(2) by android
V/WebViewChromiumFactoryProvider( 6418): Binding Chromium to main looper Looper (main, tid 1) {67216f}
I/LibraryLoader( 6418): Expected native library version number "",actual native library version number ""
I/chromium( 6418): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6418): Initializing chromium process, singleProcess=true
W/art     ( 6418): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6418): ApplicationContext is null in ApplicationStatus
W/chromium( 6418): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6418): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6418): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6418): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6418): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6418): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6418): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6418): Remote Branch: 
I/Adreno-EGL( 6418): Local Patches: 
I/Adreno-EGL( 6418): Reconstruct Branch: 
I/qtaguid ( 6249): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6249): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6249): untagSocket(41) failed with errno -22
V/AudioPolicyService(  283): registerClient() client 0xb39ab7c0, uid 10316
D/BluetoothManagerService(  839): Message: 20
D/BluetoothManagerService(  839): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13b68f6e:true
D/BluetoothAdapterService(24012171)( 2026): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@e6bd8b9
,W/ResourcesManager( 6249): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6249): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/art     ( 6418): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6418): onDetachedFromWindow called when already detached. Ignoring
,W/ResourcesManager( 6249): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/SystemWebViewEngine( 6418): CordovaWebView is running on device made by: LGE
W/art     ( 6418): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6418): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 6418): Activity.onPostResume() called 
,D/OpenGLRenderer( 6418): Render dirty regions requested: true
I/OpenGLRenderer( 6418): Initialized EGL, version 1.4
D/OpenGLRenderer( 6418): Enabling debug mode 0
,D/Finsky  ( 6249): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{19255ecc type 0 when 1453125201246 com.android.vending} when 1453125201246
,D/Atlas   ( 6418): Validating map...
D/SplitWindow(  839): check instance of lgWin Window{344eb02a u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6418): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  839): Focus entered window: Window{344eb02a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  839): Displayed com.test.thalitest/.MainActivity: +1s280ms
,W/InputMethodManagerService(  839): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/Timeline(  839): Timeline: Activity_windows_visible id: ActivityRecord{17d94e28 u0 com.test.thalitest/.MainActivity t222} time:97335
I/Timeline( 6418): Timeline: Activity_idle id: android.os.BinderProxy@31aa430a time:97359
,D/Finsky  ( 6249): [784] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1731): client connected with version: 8296000
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,D/Finsky  ( 6249): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6249): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 6249): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6249): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6249): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6249): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 6249): propertyValue:false
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/BindingManager( 6418): Cannot call determinedVisibility() - never saw a connection for the pid: 6418
,I/ActivityManager(  839): Killing 5859:com.google.android.talk/u0a61 (adj 15): empty #11
,D/JsMessageQueue( 6418): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  839): Killing 6106:com.android.providers.calendar/u0a14 (adj 15): empty #12
,W/libprocessgroup(  839): failed to open /acct/uid_10061/pid_5859/cgroup.procs: No such file or directory
,W/libprocessgroup(  839): failed to open /acct/uid_10014/pid_6106/cgroup.procs: No such file or directory
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:21.933 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  839): Process com.android.contacts (pid 6183) has died
,D/jxcore_app_log( 6418): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622850048
D/JX-Cordova( 6418): jxcore cordova android initializing
,D/UEI.SmartControl( 6276): Internal timer expired: 1
,I/art     ( 6418): CheckpointMarkThreadRoots callback created = 0x9c1baa20
,I/art     ( 6418): CheckpointMarkThreadRoots callback created = 0x9c1ba9f0
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/jxcore-log( 6418): Initializing JXcore engine
,W/jxcore-log( 6418): JXcore engine is ready
W/jxcore-log( 6418): Starting JXcore engine
,W/.test.thalitest( 6418): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7300]" dev="sockfs" ino=7300 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6418): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6418): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6821]" dev="sockfs" ino=6821 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6418): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6418): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6418): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25212]" dev="sockfs" ino=25212 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6418): Platform android
W/jxcore-log( 6418): 
,W/jxcore-log( 6418): Process ARCH arm
W/jxcore-log( 6418): 
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:24.945 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{3582a40b type 0 when 1453125205370 com.google.android.googlequicksearchbox} when 1453125205370
,D/CAR.SERVICE( 6357): mConnectedToCar = false, abort
,E/ActivityThread( 6357): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2a2b27a4 that was originally bound here
E/ActivityThread( 6357): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2a2b27a4 that was originally bound here
E/ActivityThread( 6357): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6357): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6357): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6357): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6357): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6357): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6357): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6357): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6357): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6357): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6357): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6357): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6357): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6357): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6357): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6357): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6357): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6357): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6357): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6357): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 6357): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1053552f that was originally bound here
E/ActivityThread( 6357): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1053552f that was originally bound here
E/ActivityThread( 6357): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6357): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6357): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6357): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6357): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6357): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6357): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6357): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6357): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6357): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6357): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6357): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6357): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6357): 	at android.app.ActivityThread.acce,ss$1900(ActivityThread.java:155)
E/ActivityThread( 6357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6357): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6357): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6357): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6357): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6357): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  839): Unbind failed: could not find connection for android.os.BinderProxy@21d62e8
,I/jxcore-log( 6418): JXcore Cordova bridge is ready!
I/jxcore-log( 6418): 
W/jxcore-log( 6418): JXcore engine is started
,I/chromium( 6418): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 6418): Skipped 199 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 6418): Toggling radios to true
I/jxcore-log( 6418): 
,D/BluetoothAdapter( 6418): enable(): BT is already enabled..!
D/WifiServiceImplEx(  839): setWifiEnabled: true pid=6418, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  839): setWifiEnabled: true pid=6418, uid=10316
D/WifiServiceImplEx(  839): disconnect pid=6418, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  839): reconnect pid=6418, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6418): Radios toggled
I/jxcore-log( 6418): 
I/jxcore-log( 6418): My device name is: LGE-LG-D722
I/jxcore-log( 6418): 
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2784): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2784): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  839): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  839): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1804): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,D/LGWifiP2pService(  839): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  839): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  839): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  279): Clearing all IP addresses on wlan0
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1731): Read error: ssl=0xaaede400: I/O error during system call, Connection timed out
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1731): SSL shutdown failed: ssl=0xaaede400: I/O error during system call, Broken pipe
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
,D/WifiHS20(  839): hidePasspointNotification off =false
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:26.086 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/ConnectivityService(  839): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,I/ActivityManager(  839): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6536 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/WifiStateMachine(  839): Start Disconnecting Watchdog 1
D/WifiHS20(  839): hidePasspointNotification off =false
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:26.155 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  839): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): ValidatedState{ when=-8ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): DefaultState{ when=-14ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Forcing reevaluation
I/wpa_supplicant( 2784): wlan0: CTRL-EVENT-SCAN-STARTED 
D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/ConnectivityService(  839): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  839): disableDataServiceNotify
D/DSQN    (  839): stop dsqn bin
D/WifiHS20(  839): hidePasspointNotification off =false
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:26.193 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  839): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
,D/ConnectivityService(  839): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  839): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  839): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  839): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  839): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1840): |CORE| No family connected
,D/Tethering(  839): MasterInitialState.processMessage what=3
D/WifiNetworkAgent(  839): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  839): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  839): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  839): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  839): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = -1
D/DhcpStateMachine(  839): StoppedState
,D/DhcpStateMachine(  839): StoppedState{ when=-64ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  839): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiHS20(  839): hidePasspointNotification off =false
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:26.237 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/NetworkManagementService(  839): Removing idletimer
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:26.24 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/TelephonyNetworkFactory-1( 1750): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateDISCONNECTED
D/WIFI    (  839): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  839):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings(  839): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  839): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateSCANNING
,D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2026): Disconnected process message: 10, size: 0
W/ResourcesManager( 6536): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6536): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6536): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6536): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6536): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
D/charger_monitor(  485): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2026): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ActivityManager(  839): Process com.android.gallery3d (pid 6163) has died
,I/IndexDatabaseHelper( 6536): Using schema version: 115
I/IndexDatabaseHelper( 6536): Index is fine
V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
I/ActivityManager(  839): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6559 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6559): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6559): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6559): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
I/PCSuite ( 6559): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6559): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6559): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
I/PCSuite ( 6559): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6559): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6559): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6581 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  839): Killing 6136:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_6136/cgroup.procs: No such file or directory
,W/ResourcesManager( 6581): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2784): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2784): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:27.375 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/wpa_supplicant( 2784): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2784): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:27.401 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:27.408 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:27.414 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,D/LocSvc_java(  839): onReceive
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  275): 
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/WifiServiceExtension(  839): setVHTCapabilityType  : false
,I/WifiServerServiceExt(  839): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  839): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  839): setSecurityType  : 2
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:27.486 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:27.489 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/ConnectivityService(  839): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  839): Got NetworkAgent Messenger
D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  839): NetworkAgent connected
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
E/WifiConfigStore(  839): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Babel_SMS( 6581): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6581): MmsConfig.loadMmsSettings
E/WifiConfigStore(  839): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Babel_SMS( 6581): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6581): MmsConfig.loadFromDatabase
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Setting iface cfg
E/WifiStateMachine(  839): Start Dhcp Watchdog 2
D/DhcpStateMachine(  839): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  839): WaitBeforeStartState
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateASSOCIATED
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateGROUP_HANDSHAKE
,D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/Babel_SMS( 6581): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6581): MmsConfig.loadFromResources
E/Babel_SMS( 6581): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6581): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6581): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6581): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6581): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6581): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6581): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6581): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6581): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6581): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6581): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6581): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6581): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6581): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6581): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6581): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6581): found sensor: LGE Relative Motion Detector Sensor, handle=34
,D/SensorManager( 6581): found sensor: Motion Accel, handle=46
W/Settings( 6581): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6581): startup - clean
E/WifiStateMachine(  839): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  839): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  839): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService(  839): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1126fbe3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1126fbe3 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  839): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  839): DHCP Start wake lock is acquired.
D/CommandListener(  279): Setting iface cfg
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  839): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateCOMPLETED
D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LGWifiP2pService(  839): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  839): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService(  839): ignoring duplicate network state non-change
I/Babel   ( 6581): deleted: false for 0
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
I/art     ( 6581): CheckpointMarkThreadRoots callback created = 0xb042d8d0
I/art     ( 6581): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/ActivityManager(  839): Process com.google.android.apps.plus (pid 6225) has died
,D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  839): Adding iface wlan0 to network 101
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:27.754 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,E/WifiStateMachine(  839): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService(  839): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  839): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  839): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:27.774 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
E/Netd    (  279): netlink response contains error (File exists)
D/ConnectivityService(  839): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  839): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  839): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  839): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  839): [PASSPOINT] passpointNotification: hs20AP list is checked
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:27.783 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiHS20(  839): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat(  839): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  839): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  839):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Connected
D/ConnectivityService(  839):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  839):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  839): currentScore = 0, newScore = 20
D/ConnectivityService(  839):    accepting network in place of null
D/ConnectivityService(  839): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/TelephonyNetworkFactory-1( 1750): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,E/ConnectivityService(  839): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  839): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI    (  839): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  839):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  839): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  839): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  839): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:27.801 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  839): validation of new default Network = false
,D/ConnectivityService(  839): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  839): enableDataServiceNotify 
D/DSQN    (  839): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
D/Tethering(  839): MasterInitialState.processMessage what=3
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = true, mWifiLevel = 2
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] wait 500ms before dns check
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
V/NetworkPolicy(  839): [LG_RESTRICTED] checkMobilePolicy_type()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/DSQN    ( 6627): DSQN samuel.seo ver 141203
E/DSQN    ( 6627): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6627): created command queue thread
I/DSQN    ( 6627): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6627): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityService(  839): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524290
D/DhcpStateMachine(  839): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  839): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  839): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6631): version 5.5.6 starting
,D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
E/dhcpcd  ( 6631): get_duid: Read-only file system
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
I/PCSuite ( 6559): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6559): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6559): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/AudioCapabilities( 6581): Unsupported mime audio/x-lg-flac
V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6581): Unsupported mime audio/adpcm
W/AudioCapabilities( 6581): Unsupported mime audio/g726
D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
W/AudioCapabilities( 6581): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6581): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6581): Unsupported mime video/mjpg
W/VideoCapabilities( 6581): Unsupported mime video/theora
I/dhcpcd  ( 6631): wlan0: rebinding lease of 192.168.1.134
V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6536): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
W/AudioCapabilities( 6581): Unsupported mime audio/evrc
,V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6581): Unsupported mime audio/qcelp
D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
W/VideoCapabilities( 6581): Unrecognized profile 2130706433 for video/avc
,V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
W/AudioCapabilities( 6581): Unsupported mime audio/amr-wb-plus
,V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6581): Unsupported mime audio/qcelp
W/AudioCapabilities( 6581): Unsupported mime audio/evrc
D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6581): Unsupported mime video/mp4v-esdp
D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/VideoCapabilities( 6581): Unsupported profile 4 for video/mp4v-es
D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
W/VideoCapabilities( 6581): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6581): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6581): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6581): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
I/PCSuite ( 6559): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6559): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/vclib   ( 6581): onServiceConnected
W/Babel   ( 6581): Attempted to change video mute state without an active call.
V/WiFiOffLoadBroadcast( 6536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6536): MCCMNC not supported: null
I/PCSuite ( 6559): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6559): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/NotificationManager( 6581): com.google.android.talk: cancel(10436) by com.google.android.talk
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] DNSResolver start dns
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  839): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 6627): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6627): restart monitoring
,D/LGDataListener(  279): argv[0]=dsqncommand
D/LGDataListener(  279): argv[1]=wlan0
D/LGDataListener(  279): argv[2]=1
D/LGDataListener(  279): notifyDSQN DSQN STARTMONITOR wlan0 1
,I/DSQN    ( 6627): dsqn report finish
D/DSQN    (  839): DSQM DsqnNotification wlan0  1
D/DSQN    (  839): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 13:53:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453125208408], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453125208384]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Validated
D/ConnectivityService(  839): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  839):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  839): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  839): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  839): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  839): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524290
I/WifiServerServiceExt(  839): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  839): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  839):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1750): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  839): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  839): onReceive
D/LocSvc_java(  839): got connectivity action
,D/LocSvc_java(  839): broadcast - no network connections
D/LocSvc_java(  839): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  839): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  839): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  839): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  839): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  839): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6649 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider(  839): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  839): onReceive
D/LocSvc_java(  839): got connectivity action
D/LocSvc_java(  839): broadcast - no network connections
D/LocSvc_java(  839): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  839): Sending msg: 4 arg1:0 arg2:1
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  839): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  839): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  839): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  839): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  839): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  839): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/dhcpcd  ( 6631): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  839): identical MTU - not setting
D/Nat464Xlat(  839): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  839): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  839): enableDataServiceNotify 
D/DSQN    (  839): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524295
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:29.401 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/dhcpcd  ( 6631): wlan0: leased 192.168.1.134 for 86400 seconds
D/DSQN    (  839): dsqn is running restart
,I/DSQN    ( 6680): DSQN samuel.seo ver 141203
E/DSQN    ( 6680): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6680): created command queue thread
I/DSQN    ( 6680): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6680): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/MusicStore( 6649): Database version: 120
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  839): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  839): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  839): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  839): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  839): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  839): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  839): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  839): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  839): RunningState
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6649): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6649): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6649): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6649): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6649): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6649): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  839): Process com.google.android.gms:car (pid 6357) has died
,W/ActivityThread( 6649): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6649): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@88e9e58: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6649): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6649): GMSCore installation verified
I/ConfigStore( 6649): Config Database version: 1
,I/MediaRouter( 6649): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6649): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6649): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6649): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6724 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6649): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6649): Using platform SSLCertificateSocketFactory
I/NotificationManager( 6649): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6724): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6724): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6724): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 14:53:30.582 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     (  839): Explicit concurrent mark sweep GC freed 76591(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.087ms total 211.977ms
,I/LGEmail ( 6724): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,V/WifiInternetCheck(  839): Single check msg out of sync, ignoring.
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{9632e31 type 2 when 106709 com.google.android.gms} when 106709
,D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  839): onReceive
D/LocSvc_java(  839): got connectivity action
D/LocSvc_java(  839): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  839): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  839): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  839): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  839): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  839): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 6649): type=WIFI subType= reason=null isConnected=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/LGEmail ( 6724): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/GpsLocationProvider(  839): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  839): Process com.android.vending (pid 6249) has died
,I/jxcore-log( 6418): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6418): 
,D/eas_req ( 6724): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  839): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6773 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6724): JNI_OnLoad()
,I/HubEmail( 6724): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6724): registerNatives()
I/HubEmail( 6724): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6724): registerNativeMethods()
I/HubEmail( 6724): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6724): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6724): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6773): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6773): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6773): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6773): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6773): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6773): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6773): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6773): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6797 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6773): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6773): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6773): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6773): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6773): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6773): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  839): Killing 6208:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10069/pid_6208/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/AppUp4:AppBoxCP( 6797): onCreate
,W/AppUp4:DB( 6797):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6797):  setFingerPrint start
I/AppUp4:DB( 6797):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6797):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6797):  SDK version = 0
I/AppUp4:DB( 6797):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6797): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6797): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6797): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6797): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6797): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6797): onReceive
I/AppUp4:CustModeStarterReceiver( 6797): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6797): Context : android.app.ReceiverRestrictedContext@22f33e7c
,D/AppUp4:CustFacade( 6797): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6797): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6797): begin check event
I/AppUp4:CustModeStarterReceiver( 6797): Event For GoodConnectivity
I/jxcore-log( 6418): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6418): 
D/AppUp4:CustModeStarterReceiver( 6797): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,I/jxcore-log( 6418): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6418): 
D/AppUp4:CustModeStarterReceiver( 6797): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6797): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6797): handleAsyncCustNotification do not startCustService
I/ActivityManager(  839): Killing 6581:com.google.android.talk/u0a61 (adj 15): empty #11
I/jxcore-log( 6418): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6418): 
,W/libprocessgroup(  839): failed to open /acct/uid_10061/pid_6581/cgroup.procs: No such file or directory
,I/jxcore-log( 6418): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6418): 
I/jxcore-log( 6418): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6418): 
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/LgeMiscReceiver( 3155): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/jxcore-log( 6418): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6418): 
,I/LgeMiscReceiver( 3155): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3155): networkInfo.isConnected() = false
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out(  839): propertyValue:false
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  839): propertyValue:false
,I/DSQN    ( 6680): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6680): restart monitoring
,D/LGDataListener(  279): argv[0]=dsqncommand
D/LGDataListener(  279): argv[1]=wlan0
D/LGDataListener(  279): argv[2]=1
D/LGDataListener(  279): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6680): dsqn report finish
I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6822 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
D/DSQN    (  839): DSQM DsqnNotification wlan0  1
D/DSQN    (  839): start to monitor internet connection
V/WifiInternetCheck(  839): isHttpConnectionAvailable - We got a valid response : 204
,D/PhoneMonitor( 6822): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6822): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6822): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  839): Killing 6536:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_6536/cgroup.procs: No such file or directory
,I/CheckinService( 4240): Checkin interval check for package: unspecified last checkin: 1453125185374 min interval config: 0 actual interval: 27013
,I/CheckinService( 4240): Checking schedule, now: 1453125212395 next: 1453125215186
I/CheckinService( 4240): active receiver: disabled
,D/PhoneMonitor( 6822): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/DownloadManager( 3228): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/TelephonyAutoProfiling( 6822): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6822): [parse] Load xml
V/DownloadManager( 3228): DownloadService onCreate
,I/DownloadManager( 3228): in removeSpuriousFiles
I/ActivityManager(  839): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6849 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/NotificationManager( 3228): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3228): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/TelephonyAutoProfiling( 6822): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6822): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@39b02799 on behalf of 3228
V/DownloadManager( 3228): DownloadService onStartCommand
,V/DownloadManager( 3228): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3228): in trimDatabase
V/DownloadManager( 3228): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@2359830c on behalf of 3228
V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@3a52a455 on behalf of 3228
D/PhoneMonitor( 6822): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3228): DownloadService onDestroy
,I/ActivityManager(  839): Killing 6276:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5824): android.os.DeadObjectException
W/System.err( 5824): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5824): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5824): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5824): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5824): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5824): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5824): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5824): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5824): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5824): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5824): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 5824): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5824): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5824): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5824): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5824): android.os.DeadObjectException
W/System.err( 5824): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5824): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5824): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5824): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5824): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5824): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5824): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5824): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5824): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5824): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5824): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5824): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5824): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5824): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5824): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/jxcore-log( 6418): Test app app.js loaded
I/jxcore-log( 6418): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6418): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6418): BLE advertisement is supported
I/jxcore-log( 6418): 
,W/libprocessgroup(  839): failed to open /acct/uid_10089/pid_6276/cgroup.procs: No such file or directory
,W/ActivityManager(  839): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/WeatherAncestor( 2672): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:32
D/UpdateThreadPoolManager( 2672): 2 : This is isUpdating : false
D/WeatherAncestor( 2672): connectivity changed - connection : true
D/Weather_cast( 2672): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2672): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:32
D/WeatherService( 2672): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/chromium( 6418): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  839): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6880 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6897 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2672): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  308): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 337us total 22.491ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 24.909ms
D/WeatherService( 2672): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2672): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 27.900ms
,W/ResourcesManager( 6897): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6880): Quickset Services start...
,I/UEI.SmartControl( 6880): Manufacture = LGE
D/UEI.SmartControl( 6880): File observer start...
E/UEI.SmartControl( 6880): IR Port is disabled: false
,D/UEI.SmartControl( 6880): Starting file observer...
D/UEI.SmartControl( 6880): Extracting JNI libs...
D/UEI.SmartControl( 6880): --- this system supports 32-bit or 64-bit only
,I/Babel_SMS( 6897): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6897): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6897): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6897): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6897): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6897): MmsConfig.loadFromResources
E/Babel_SMS( 6897): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6897): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6897): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6897): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6897): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6897): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6897): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6897): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6897): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6897): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6897): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6897): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6897): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6897): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6897): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6897): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6897): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6897): found sensor: Motion Accel, handle=46
,W/art     ( 6897): Suspending all threads took: 6.616ms
,W/Settings( 6897): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/UEI.SmartControl( 6880): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6880): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6880): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/Babel_Crash( 6897): startup - clean
I/art     ( 6897): CheckpointMarkThreadRoots callback created = 0xb042d8b0
I/Babel   ( 6897): deleted: false for 0
,I/UEI.SmartControl( 6880): --- Selecting new region: 2
I/UEI.SmartControl( 6880): -- Running on KitKat(19) and above! JNI will be used.
,I/art     ( 6897): CheckpointMarkThreadRoots callback created = 0xb042d880
D/UEI.SmartControl( 6880): Platform has CIR...
D/UEI.SmartControl( 6880): NO CIR support, need to check package...
I/UEI.SmartControl( 6880): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 6880): QS Service created
E/UEI.SmartControl( 6880): QS start get config
,I/ActivityManager(  839): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6931 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6880): Loading JNI Libs...
,D/UEI.SmartControl( 6880):  configuring local db...
W/AudioCapabilities( 6897): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6897): Unsupported mime audio/adpcm
W/AudioCapabilities( 6897): Unsupported mime audio/g726
W/AudioCapabilities( 6897): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6897): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6897): Unsupported mime video/mjpg
,W/VideoCapabilities( 6897): Unsupported mime video/theora
,W/AudioCapabilities( 6897): Unsupported mime audio/evrc
W/AudioCapabilities( 6897): Unsupported mime audio/qcelp
W/VideoCapabilities( 6897): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6897): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6897): Unsupported mime audio/qcelp
W/AudioCapabilities( 6897): Unsupported mime audio/evrc
,W/VideoCapabilities( 6897): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6897): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6897): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6897): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6897): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6897): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6897): onServiceConnected
,W/Babel   ( 6897): Attempted to change video mute state without an active call.
I/NotificationManager( 6897): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6897): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6897): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6897): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6897): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6897): propertyValue:false
I/Babel   ( 6897): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  839): Killing 6559:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6880):  ---- Has DB8: true
,D/UEI.SmartControl( 6880): QS start statue = true Error code = 0
D/UEI.SmartControl( 6880): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6880): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6880): IRRCDataComm has AudioManager!!!!.
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_6559/cgroup.procs: No such file or directory
W/irrc_jni( 6880): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6880): IrrcClient ++ 
D/irrcClient( 6880): getIrrcService ++ 
D/irrcClient( 6880): getIrrcService -- 
D/irrcClient( 6880): IrrcClient -- 
W/irrc_jni( 6880): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6880): Services init done
I/UEI.SmartControl( 6880): Device manager: loading config....
D/UEI.SmartControl( 6880): QS Service init finished
D/UEI.SmartControl( 6880): QS Service version name: 0.1.73
D/UEI.SmartControl( 6880): QS Service version code: 1073
D/UEI.SmartControl( 6880): Config is loaded...
D/UEI.SmartControl( 6880): Service requested: Control
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6931): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6931): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/UEI.SmartControl( 6880):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6880): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6880): Request IControl service: devices are loaded...
I/ActivityManager(  839): Killing 5824:com.lge.qremote/u0a106 (adj 15): empty #11
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6931): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 6931): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6931):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6931):   adb logcat -s GAv4
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6931): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/UEI.SmartControl( 6880): Internal service binding...
W/libprocessgroup(  839): failed to open /acct/uid_10106/pid_5824/cgroup.procs: No such file or directory
,W/GAv4    ( 6931): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6931): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6931): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6931): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6931): Time to load native libraries: 2 ms (timestamps 236-238)
I/LibraryLoader( 6931): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6931): Binding Chromium to main looper Looper (main, tid 1) {373d2909}
I/LibraryLoader( 6931): Expected native library version number "",actual native library version number ""
I/chromium( 6931): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6931): Initializing chromium process, singleProcess=true
W/art     ( 6931): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6931): ApplicationContext is null in ApplicationStatus
W/chromium( 6931): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6931): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6931): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6931): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6931): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6931): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6931): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6931): Remote Branch: 
I/Adreno-EGL( 6931): Local Patches: 
I/Adreno-EGL( 6931): Reconstruct Branch: 
V/AudioPolicyService(  283): registerClient() client 0xb551c940, uid 10079
,I/NSApplication( 6931): Starting up...
,W/AudioManagerAndroid( 6931): Requires BLUETOOTH permission
I/ActivityManager(  839): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7000 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6649:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10081/pid_6649/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7019 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6724:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10021/pid_6724/cgroup.procs: No such file or directory
,W/ResourcesManager( 7019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/AlarmManager(  839): RTC_WAKEUP set : Alarm{177b7599 type 0 when 1453125215186 com.google.android.gms} when 1453125215186
,I/ActivityManager(  839): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7041 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{175fa90c type 0 when 1453125215257 com.android.vending} when 1453125215257
,I/ActivityManager(  839): Killing 6773:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_6773/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7066 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 7041): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/MusicStore( 7066): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7066): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/Finsky  ( 7041): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7041): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7041): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7041): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3228): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@1e669f5b on behalf of 7041
D/Finsky  ( 7041): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7041): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7041): Skipping gmscore version check
D/Finsky  ( 7041): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 7041): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7066): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7066): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{277e734b type 0 when 1453125215824 com.google.android.googlequicksearchbox} when 1453125215824
W/ResourcesManager( 7066): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7066): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  839): Process com.lge.appbox.client (pid 6797) has died
,D/Finsky  ( 7041): [865] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7041): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/JNIHelp ( 7066): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 7066): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7066): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@88e9e58: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7066): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7066): GMSCore installation verified
I/ConfigStore( 7066): Config Database version: 1
,I/MediaRouter( 7066): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7066): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7066): type=WIFI subType= reason=null isConnected=true
,I/art     (  839): Explicit concurrent mark sweep GC freed 32058(1631KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.075ms total 155.906ms
,I/NetworkMonitor( 7066): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7134 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7066): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7066): Using platform SSLCertificateSocketFactory
I/ActivityManager(  839): Killing 6822:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/ResourcesManager( 7134): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7134): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7134): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_6822/cgroup.procs: No such file or directory
,I/NotificationManager( 7066): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7134): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7134): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/eas_req ( 7134): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  839): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7163 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7134): JNI_OnLoad()
I/HubEmail( 7134): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 7134): registerNatives()
I/HubEmail( 7134): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7134): registerNativeMethods()
I/HubEmail( 7134): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7134): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7134): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  839): Killing 6849:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10051/pid_6849/cgroup.procs: No such file or directory
,D/LGDMClient( 7163): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7163): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7163): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7163): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 7163): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7163): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 7163): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7163): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7187 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7163): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7163): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7163): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7163): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7163): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7163): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  839): Killing 6880:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10089/pid_6880/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7187): onCreate
,W/AppUp4:DB( 7187):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7187):  setFingerPrint start
I/AppUp4:DB( 7187):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7187):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7187):  SDK version = 0
I/AppUp4:DB( 7187):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7187): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7187): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7187): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7187): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7187): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7187): onReceive
I/AppUp4:CustModeStarterReceiver( 7187): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7187): Context : android.app.ReceiverRestrictedContext@22f33e7c
,D/AppUp4:CustFacade( 7187): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7187): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7187): begin check event
I/AppUp4:CustModeStarterReceiver( 7187): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7187): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7187): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7187): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7187): handleAsyncCustNotification do not startCustService
I/ActivityManager(  839): Killing 6897:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10061/pid_6897/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3155): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3155): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3155): networkInfo.isConnected() = false
I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7206 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7206): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7206): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7206): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  839): Killing 6931:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
D/PhoneMonitor( 7206): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7206): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7206): [parse] Load xml
V/TelephonyAutoProfiling( 7206): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7206): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7206): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  839): failed to open /acct/uid_10079/pid_6931/cgroup.procs: No such file or directory
,V/DownloadManager( 3228): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3228): DownloadService onCreate
I/DownloadManager( 3228): in removeSpuriousFiles
,V/DownloadManager( 3228): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3228): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@11a1c3f8 on behalf of 3228
I/DownloadManager( 3228): in trimDatabase
V/DownloadManager( 3228): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@156630d1 on behalf of 3228
I/ActivityManager(  839): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7231 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3228): DownloadService onStartCommand
V/DownloadManager( 3228): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 4240): Checkin interval check for package: unspecified last checkin: 1453125185374 min interval config: 0 actual interval: 32227
,V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@2a2b27a4 on behalf of 3228
I/CheckinService( 4240): Checking schedule, now: 1453125217617 next: 1453125215186
I/CheckinService( 4240): active receiver: enabled
,I/CheckinService( 4240): Preparing to send checkin request
I/EventLogService( 4240): Accumulating logs since 1453125198309
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/WeatherAncestor( 2672): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:37
D/UpdateThreadPoolManager( 2672): 2 : This is isUpdating : false
D/WeatherAncestor( 2672): connectivity changed - connection : true
D/Weather_cast( 2672): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2672): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:37
D/WeatherService( 2672): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/CheckinRequestBuilder( 4240): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7256 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2672): 2 : Utils getTopActivity com.lge.launcher2 / true
E/ActivityThread( 4240): Failed to find provider info for com.google.android.wearable.settings
V/DownloadManager( 3228): DownloadService onDestroy
,D/WeatherService( 2672): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2672): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 21.781ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.300ms
,W/ResourcesManager( 7256): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.012ms
D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 113767319334; DSPS: 3826460; Offset : -3008731641
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  839): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7275 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 7275): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7275): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Babel_SMS( 7256): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7256): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7256): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7256): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7256): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7256): MmsConfig.loadFromResources
E/Babel_SMS( 7256): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7256): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7256): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7256): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7256): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7256): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7256): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7256): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7256): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7256): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7256): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7256): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7256): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7256): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7256): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7256): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7256): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7256): found sensor: Motion Accel, handle=46
,W/Settings( 7256): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7256): startup - clean
I/MultiDex( 7275): VM with version 2.1.0 has multidex support
I/MultiDex( 7275): install
I/MultiDex( 7275): VM has multidex support, MultiDex support library is disabled.
,I/Babel   ( 7256): deleted: false for 0
,V/JNIHelp ( 7275): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     ( 7256): CheckpointMarkThreadRoots callback created = 0xb042d520
,I/art     ( 7256): CheckpointMarkThreadRoots callback created = 0xb042d500
,I/ActivityManager(  839): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7308 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityThread( 7275): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7275): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39b02799: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7275): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7275): com.google.android.gms: cancel(10436) by com.google.android.gms
,W/AudioCapabilities( 7256): Unsupported mime audio/x-lg-flac
I/NotificationManager( 7275): com.google.android.gms: cancel(39789) by com.google.android.gms
W/AudioCapabilities( 7256): Unsupported mime audio/adpcm
W/AudioCapabilities( 7256): Unsupported mime audio/g726
W/AudioCapabilities( 7256): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7256): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7256): Unsupported mime video/mjpg
W/VideoCapabilities( 7256): Unsupported mime video/theora
,W/AudioCapabilities( 7256): Unsupported mime audio/evrc
W/AudioCapabilities( 7256): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7256): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7256): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7256): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7256): Unsupported mime audio/evrc
I/art     ( 7275): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7275): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/VideoCapabilities( 7256): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7256): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7256): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7256): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7256): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7256): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7256): onServiceConnected
,W/Babel   ( 7256): Attempted to change video mute state without an active call.
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7308): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/NativeLibraryUtils( 7275): Install completed successfully. count=14 extracted=0
,I/GAv4    ( 7308): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7308):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7308):   adb logcat -s GAv4
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7308): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/NotificationManager( 7256): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7256): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7256): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7256): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7256): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 7256): propertyValue:false
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7308): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7308): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7308): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/WVCdm   (  283): Instantiating CDM.
,I/WVCdm   (  283): CdmEngine::OpenSession
I/WVCdm   (  283): Level3 Library Dec 11 2014 16:13:16
W/GAv4    ( 7308): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7308): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 7256): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  839): Killing 7000:com.android.chrome/u0a48 (adj 15): empty #11
W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  283): Properties::GetOEMCryptoPath: null. applies level3
,W/WVCdm   (  283): L1 library not specified. Falling Back to L3
W/libprocessgroup(  839): failed to open /acct/uid_10048/pid_7000/cgroup.procs: No such file or directory
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=3528547845
I/WebViewFactory( 7308): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7308): Time to load native libraries: 2 ms (timestamps 5004-5006)
I/LibraryLoader( 7308): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7308): Binding Chromium to main looper Looper (main, tid 1) {373d2909}
I/LibraryLoader( 7308): Expected native library version number "",actual native library version number ""
I/chromium( 7308): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7308): Initializing chromium process, singleProcess=true
W/art     ( 7308): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7308): ApplicationContext is null in ApplicationStatus
,W/chromium( 7308): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7308): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7308): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7308): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7308): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7308): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7308): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7308): Remote Branch: 
I/Adreno-EGL( 7308): Local Patches: 
I/Adreno-EGL( 7308): Reconstruct Branch: 
I/art     ( 7275): CheckpointMarkThreadRoots callback created = 0xb04d3e40
,I/NSApplication( 7308): Starting up...
I/art     ( 7275): CheckpointMarkThreadRoots callback created = 0xb04d3e20
,V/AudioPolicyService(  283): registerClient() client 0xb551c920, uid 10079
,W/AudioManagerAndroid( 7308): Requires BLUETOOTH permission
I/ActivityManager(  839): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7373 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 7019:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/dex2oat ( 7371): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  839): failed to open /acct/uid_10086/pid_7019/cgroup.procs: No such file or directory
,I/dex2oat ( 7371): dex2oat took 119.279ms (threads: 4)
,I/Adreno-EGL( 7275): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7275): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7275): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7275): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7275): Remote Branch: 
I/Adreno-EGL( 7275): Local Patches: 
I/Adreno-EGL( 7275): Reconstruct Branch: 
,I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7397 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 7041:com.android.vending/u0a36 (adj 15): empty #11
,I/Adreno-EGL( 7275): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7275): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7275): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7275): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7275): Remote Branch: 
I/Adreno-EGL( 7275): Local Patches: 
I/Adreno-EGL( 7275): Reconstruct Branch: 
,W/libprocessgroup(  839): failed to open /acct/uid_10036/pid_7041/cgroup.procs: No such file or directory
,W/ResourcesManager( 7397): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     (  839): Explicit concurrent mark sweep GC freed 14069(682KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 9.784ms total 151.620ms
,I/WVCdm   (  283): CdmEngine::OpenSession
,I/ActivityManager(  839): Killing 7066:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10081/pid_7066/cgroup.procs: No such file or directory
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  839): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7428 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7428): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7428): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/MusicWidget( 2647): mDelayedStopHandler : unbind
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 1731): propertyValue:false
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7428): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7428): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/MusicBrowser( 2689): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2689): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2689): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2689): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2689): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2689): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2689): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2689): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,W/ResourcesManager( 7428): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7428): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/MediaFocusControl(  839):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@31aa430acom.lge.music.MediaPlaybackService$6@29a7c77b
D/MusicBrowser( 2689): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2689): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2689): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2689): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2689): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1373c668
I/MusicBrowser( 2689): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2689): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2689): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2689): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2689): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2689): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2689): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2689): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2689): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2689): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2689): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2689): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2689): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2689): reset
V/JNIHelp ( 7428): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/MediaPlayer[Native]( 2689): setListener
V/MediaPlayer[Native]( 2689): disconnect
V/MediaPlayer[Native]( 2689): destructor
V/AudioFlinger(  283): releasing 19 from 2689 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/MediaPlayer[Native]( 2689): disconnect
D/MusicBrowser( 2689): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/SmartShareClient( 2689): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2689): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2689): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2689): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2689): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2689): [SmartShareManagerClient] unregisterListener: 525965720
W/SmartShareClient( 2689): [SmartShareManagerClient] unregisterListener invalid listener: 525965720
I/SmartShareClient( 2689): [SmartShareManagerClient] terminate service: 2689/MediaPlaybackService/739228750
,E/HomeCloudIF( 2689): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2689): [SmartShareManagerClient] unbindService context:android.app.Application@982e5f1
V/CloudHub( 2689): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2689): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2689): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2689): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2689): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
,I/CloudHub( 2689): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
W/ActivityThread( 7428): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7428): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@88e9e58: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7428): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7428): GMSCore installation verified
I/ConfigStore( 7428): Config Database version: 1
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     ( 5705): Explicit concurrent mark sweep GC freed 1716(62KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 463us total 40.034ms
,I/WVCdm   (  283): CdmEngine::CloseSession
,I/MediaRouter( 7428): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7428): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7428): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  839): Killing 7134:com.lge.email/u0a21 (adj 15): empty #11
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=3286116983
,W/libprocessgroup(  839): failed to open /acct/uid_10021/pid_7134/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7428): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7464 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7428): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7428): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7464): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7464): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7464): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  839): Killing 7163:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_7163/cgroup.procs: No such file or directory
,I/NotificationManager( 7428): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7464): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7464): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7464): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  839): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7498 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7464): JNI_OnLoad()
I/HubEmail( 7464): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7464): registerNatives()
I/HubEmail( 7464): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7464): registerNativeMethods()
I/HubEmail( 7464): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7464): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  839): Killing 7187:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_7187/cgroup.procs: No such file or directory
,W/Settings( 7464): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7498): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7498): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7498): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7498): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7498): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7498): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7498): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7498): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7522 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7498): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7498): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7498): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7498): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 7498): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7498): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  839): Killing 7206:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_7206/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7522): onCreate
W/AppUp4:DB( 7522):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7522):  setFingerPrint start
I/AppUp4:DB( 7522):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7522):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7522):  SDK version = 0
I/AppUp4:DB( 7522):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7522): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7522): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7522): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7522): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7522): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7522): onReceive
I/AppUp4:CustModeStarterReceiver( 7522): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7522): Context : android.app.ReceiverRestrictedContext@22f33e7c
D/AppUp4:CustFacade( 7522): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7522): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7522): begin check event
I/AppUp4:CustModeStarterReceiver( 7522): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7522): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7522): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7522): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7522): handleAsyncCustNotification do not startCustService
I/ActivityManager(  839): Killing 7231:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10051/pid_7231/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3155): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3155): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3155): networkInfo.isConnected() = true
D/PhoneState( 3155): setPdpRejectCasuse : false
,I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7549 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7549): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7549): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7549): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  839): Killing 7256:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7549): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7549): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7549): [parse] Load xml
V/TelephonyAutoProfiling( 7549): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7549): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7549): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  839): failed to open /acct/uid_10061/pid_7256/cgroup.procs: No such file or directory
,V/DownloadManager( 3228): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3228): DownloadService onCreate
I/NotificationManager( 3228): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3228): in removeSpuriousFiles
V/DownloadManager( 3228): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@333000c2 on behalf of 3228
I/DownloadManager( 3228): in trimDatabase
V/DownloadManager( 3228): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@31c51a10 on behalf of 3228
,I/ActivityManager(  839): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7571 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3228): DownloadService onStartCommand
,V/DownloadManager( 3228): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@2d81670e on behalf of 3228
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/CheckinService( 4240): Checkin interval check for package: unspecified last checkin: 1453125185374 min interval config: 0 actual interval: 37339
V/DownloadManager( 3228): DownloadService onDestroy
I/ActivityManager(  839): Killing 7308:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10079/pid_7308/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2672): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:43
D/UpdateThreadPoolManager( 2672): 2 : This is isUpdating : false
D/WeatherAncestor( 2672): connectivity changed - connection : true
D/Weather_cast( 2672): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2672): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:43
D/WeatherService( 2672): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7591 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2672): 2 : Utils getTopActivity com.lge.launcher2 / true
,I/art     (  308): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 272us total 24.766ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.361ms
,D/WeatherService( 2672): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2672): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 23.638ms
,I/WVCdm   (  283): CdmEngine::CloseSession
I/WVCdm   (  283): L3 Terminate.
,W/ResourcesManager( 7591): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7591): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7591): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7591): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7591): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7591): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7591): MmsConfig.loadFromResources
E/Babel_SMS( 7591): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7591): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7591): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7591): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7591): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7591): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7591): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7591): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7591): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7591): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7591): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7591): found sensor: LGE Significant Motion Detector Sensor, handle=47
,D/SensorManager( 7591): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7591): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7591): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7591): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7591): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7591): found sensor: Motion Accel, handle=46
I/art     ( 7591): CheckpointMarkThreadRoots callback created = 0xaaf565c0
W/Settings( 7591): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7591): startup - clean
I/art     ( 7591): CheckpointMarkThreadRoots callback created = 0xaaf565a0
,I/Babel   ( 7591): deleted: false for 0
,I/Adreno-EGL( 7275): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7275): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7275): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7275): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7275): Remote Branch: 
I/Adreno-EGL( 7275): Local Patches: 
I/Adreno-EGL( 7275): Reconstruct Branch: 
,I/ActivityManager(  839): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7628 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7591): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7591): Unsupported mime audio/adpcm
W/AudioCapabilities( 7591): Unsupported mime audio/g726
W/AudioCapabilities( 7591): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7591): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7591): Unsupported mime video/mjpg
W/VideoCapabilities( 7591): Unsupported mime video/theora
,I/CheckinRequestBuilder( 4240): Classify the device as Phone.
,W/AudioCapabilities( 7591): Unsupported mime audio/evrc
,W/AudioCapabilities( 7591): Unsupported mime audio/qcelp
W/VideoCapabilities( 7591): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7591): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7591): Unsupported mime audio/qcelp
W/AudioCapabilities( 7591): Unsupported mime audio/evrc
,D/libc-netbsd( 4240): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4240): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4240): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4240): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
W/VideoCapabilities( 7591): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7591): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7591): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7591): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7591): Unrecognized profile 2130706433 for video/avc
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 4240): propertyValue:false
W/VideoCapabilities( 7591): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7591): onServiceConnected
,W/Babel   ( 7591): Attempted to change video mute state without an active call.
D/libc-netbsd( 7591): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7591): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7591): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7591): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 7591): propertyValue:false
I/NotificationManager( 7591): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/Babel   ( 7591): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  839): Killing 7373:com.android.chrome/u0a48 (adj 15): empty #11
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7628): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/libc-netbsd( 4240): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4240): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 7628): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7628):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7628):   adb logcat -s GAv4
W/ContextImpl( 7628): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7628): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
D/libc-netbsd( 4240): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4240): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ContextImpl( 7628): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/libc-netbsd( 4240): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4240): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4240): Sending checkin request (9755 bytes)
,W/libprocessgroup(  839): failed to open /acct/uid_10048/pid_7373/cgroup.procs: No such file or directory
,W/GAv4    ( 7628): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7628): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7628): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 7628): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7628): Time to load native libraries: 2 ms (timestamps 169-171)
I/LibraryLoader( 7628): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7628): Binding Chromium to main looper Looper (main, tid 1) {373d2909}
I/LibraryLoader( 7628): Expected native library version number "",actual native library version number ""
I/chromium( 7628): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7628): Initializing chromium process, singleProcess=true
W/art     ( 7628): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7628): ApplicationContext is null in ApplicationStatus
,W/chromium( 7628): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7628): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7628): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7628): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7628): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7628): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7628): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7628): Remote Branch: 
I/Adreno-EGL( 7628): Local Patches: 
I/Adreno-EGL( 7628): Reconstruct Branch: 
,I/CheckinRequestBuilder( 4240): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4240): Failed to find provider info for com.google.android.wearable.settings
,V/AudioPolicyService(  283): registerClient() client 0xb39ab960, uid 10079
,W/AudioManagerAndroid( 7628): Requires BLUETOOTH permission
,I/NSApplication( 7628): Starting up...
I/ActivityManager(  839): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7698 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  839): Explicit concurrent mark sweep GC freed 16177(779KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.596ms total 158.798ms
,I/ActivityManager(  839): Killing 7397:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10086/pid_7397/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7727 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 2689:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  283): 2689 died, releasing its sessions
V/AudioFlinger(  283):  pid 1750 @ 0
V/AudioFlinger(  283):  pid 3155 @ 1
V/AudioFlinger(  283):  pid 3155 @ 2
,W/libprocessgroup(  839): failed to open /acct/uid_10028/pid_2689/cgroup.procs: No such file or directory
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 7727): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 4240): Classify the device as Phone.
,I/CheckinTask( 4240): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4240): Checking schedule, now: 1453125224767 next: 1453652473759
I/CheckinService( 4240): active receiver: disabled
,I/CheckinService( 4240): Checking schedule, now: 1453125224816 next: 1453652473759
I/CheckinService( 4240): active receiver: disabled
,D/CheckinService( 4240): Recording last checkin time for package unspecified as 1453125224828
,I/ActivityManager(  839): Killing 7464:com.lge.email/u0a21 (adj 15): empty #11
,I/ActivityManager(  839): Killing 7428:com.google.android.music:main/u0a81 (adj 15): empty #12
,W/libprocessgroup(  839): failed to open /acct/uid_10021/pid_7464/cgroup.procs: No such file or directory
,W/libprocessgroup(  839): failed to open /acct/uid_10081/pid_7428/cgroup.procs: No such file or directory
I/ActivityManager(  839): Killing 7498:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/art     ( 7727): CheckpointMarkThreadRoots callback created = 0xb042d4c0
,I/art     ( 7727): CheckpointMarkThreadRoots callback created = 0xb042d4a0
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_7498/cgroup.procs: No such file or directory
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 4240): Checkin interval check for package: unspecified last checkin: 1453125224828 min interval config: 0 actual interval: 272
,I/CheckinService( 4240): Checking schedule, now: 1453125225119 next: 1453652473759
I/CheckinService( 4240): active receiver: disabled
,W/ContextImpl( 3620): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/WearableService( 1731): callingUid 10006, callindPid: 1731
D/LocationInitializer( 4240): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,E/MDM     ( 1731): [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
V/SetupWizard( 7549): Connected to Gservices successfully
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]QPairHandler( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/AppUp4:CustModeStarterReceiver( 7522): onReceive
I/AppUp4:CustModeStarterReceiver( 7522): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7522): Context : android.app.ReceiverRestrictedContext@22f33e7c
D/AppUp4:CustFacade( 7522): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7522): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7522): begin check event
I/AppUp4:CustModeStarterReceiver( 7522): Event For Nothing, skip.
I/NotificationManager( 7591): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7591): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7591): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/administrator(  839): Handling package changes for user 0
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  839): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7803 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
W/art     ( 7591): Suspending all threads took: 6.537ms
,V/JNIHelp ( 7591): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 7803): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7803): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7803): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/System  ( 7591): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7591): Installed default security provider GmsCore_OpenSSL
,I/NotificationService(  839): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  839): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  839): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  839): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  839): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3544a13a
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
,I/AppConfig( 7803): Total System Memory = 906309632
,I/GalleryUtils( 7803): Application Heap = 96 MB
,I/AppConfig( 7803): App Tier : NOT_DEF
D/SystemHelper( 7803): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  839): Process com.lge.drmservice (pid 7571) has died
,W/ResourcesManager(  839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  839): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7827 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7827): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7827): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7827): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7827): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7827): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  839): applying state to connected service
,I/SystemConfig( 7827): BUILD Country: EU
I/SystemConfig( 7827): BUILD Operator: OPEN
,I/ActivityManager(  839): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7850 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7827): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7827): existFile = false
I/SystemConfig( 7827): canReadFile = false
I/SystemConfig( 7827): systemFeature RCS result false
D/SystemConfig( 7827): refreshRcsSupport() :false
,I/LockScreenSettings( 7850): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7850): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7850): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7850): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7850): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7850): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  839): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7871 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 75 ms] updated apps [took 75 ms] 
,D/Finsky  ( 7871): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  839): Process com.google.android.apps.magazines (pid 7628) has died
,D/Finsky  ( 7871): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7871): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7871): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7871): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Ads     ( 7871): Skipping gmscore version check
,D/Finsky  ( 7871): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7871): [1] Libraries$2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 4240): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4240): Null package name or gms related package.  Ignoreing.
,V/DownloadManager( 3228): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@28c9c73c on behalf of 7871
I/Icing   ( 4240): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 7871): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7871): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 26836(1939KB) AllocSpace objects, 34(544KB) LOS objects, 40% free, 13MB/22MB, paused 1.577ms total 93.900ms
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 4240): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4240): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  839): Killing 7698:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10048/pid_7698/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2026): Disconnected process message: 10, size: 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,D/charger_monitor(  485): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  839): Killing 7549:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_7549/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 133768381827; DSPS: 4481855; Offset : -3008738566
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=285300386, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,D/WeatherService( 2672): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:54:0
,D/WeatherService( 2672): 2 : TimeTick Intent And Screen On
D/WeatherService( 2672): 2 : SDK version : 21
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2672): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2672): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2672): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2672): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2672): 2 : This is isUpdating : false
D/WeatherService( 2672): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2672): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2672): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2672): 2 : Fixed theme : optimus
I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
,D/WeatherReflect( 2672): 2 : Map key string is -2
D/lim     ( 2672): 2 : time = 14:54
,I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/WeatherReflect( 2672): Model Name : LG-D722
D/WeatherTheme( 2672): 2 : Different view - status_min_formatted : 53 != 54
D/WeatherTheme( 2672): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
,D/WeatherReflect( 2672): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2672): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2672): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2672): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2672): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2672): forecast size is 0
,D/Theme   ( 2672): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2672): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2672): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2672): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2672): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2672): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2672): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2672): url is : null
D/Theme   ( 2672): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2672): 2 : update view, appWidgetId: 2
,D/WeatherService( 2672): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:54:0
D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=285300386 [*alarm*], flags=0x0
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{9436f33 type 2 when 140277 com.google.android.gms} when 140277
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1731): Vacuum at: now=1453125244575 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  839): ALS enabled for SRE
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27203 ms ago)
,D/qdlights(  839): set_light_backlight: 253
,D/qdlights(  839): set_light_backlight: 250
D/qdlights(  839): set_light_backlight: 247
,D/qdlights(  839): set_light_backlight: 243
,D/qdlights(  839): set_light_backlight: 240
,D/qdlights(  839): set_light_backlight: 237
,D/qdlights(  839): set_light_backlight: 233
,D/qdlights(  839): set_light_backlight: 230
,D/qdlights(  839): set_light_backlight: 227
,D/qdlights(  839): set_light_backlight: 223
,D/qdlights(  839): set_light_backlight: 220
,D/qdlights(  839): set_light_backlight: 217
,D/qdlights(  839): set_light_backlight: 213
,D/qdlights(  839): set_light_backlight: 210
,D/qdlights(  839): set_light_backlight: 207
,D/qdlights(  839): set_light_backlight: 203
,D/qdlights(  839): set_light_backlight: 200
,D/qdlights(  839): set_light_backlight: 197
,D/qdlights(  839): set_light_backlight: 193
,D/qdlights(  839): set_light_backlight: 190
,D/qdlights(  839): set_light_backlight: 187
,D/qdlights(  839): set_light_backlight: 183
,D/qdlights(  839): set_light_backlight: 180
,D/qdlights(  839): set_light_backlight: 177
,D/qdlights(  839): set_light_backlight: 173
,D/qdlights(  839): set_light_backlight: 170
,D/qdlights(  839): set_light_backlight: 167
,D/qdlights(  839): set_light_backlight: 163
,D/qdlights(  839): set_light_backlight: 160
,D/qdlights(  839): set_light_backlight: 157
,D/qdlights(  839): set_light_backlight: 153
,D/qdlights(  839): set_light_backlight: 150
,D/qdlights(  839): set_light_backlight: 147
,D/qdlights(  839): set_light_backlight: 143
,D/qdlights(  839): set_light_backlight: 140
,D/qdlights(  839): set_light_backlight: 137
,D/qdlights(  839): set_light_backlight: 133
,D/qdlights(  839): set_light_backlight: 130
,D/qdlights(  839): set_light_backlight: 127
,D/qdlights(  839): set_light_backlight: 123
,D/qdlights(  839): set_light_backlight: 120
,D/qdlights(  839): set_light_backlight: 117
,D/qdlights(  839): set_light_backlight: 113
,D/qdlights(  839): set_light_backlight: 110
,D/qdlights(  839): set_light_backlight: 107
,D/qdlights(  839): set_light_backlight: 103
,D/qdlights(  839): set_light_backlight: 100
,D/qdlights(  839): set_light_backlight: 97
,D/qdlights(  839): set_light_backlight: 93
,D/qdlights(  839): set_light_backlight: 90
,D/qdlights(  839): set_light_backlight: 87
,D/qdlights(  839): set_light_backlight: 83
,D/qdlights(  839): set_light_backlight: 80
,D/qdlights(  839): set_light_backlight: 77
,D/qdlights(  839): set_light_backlight: 73
,D/qdlights(  839): set_light_backlight: 70
,D/qdlights(  839): set_light_backlight: 67
,D/qdlights(  839): set_light_backlight: 63
,D/qdlights(  839): set_light_backlight: 60
,D/qdlights(  839): set_light_backlight: 57
,D/qdlights(  839): set_light_backlight: 53
,D/qdlights(  839): set_light_backlight: 50
,D/qdlights(  839): set_light_backlight: 47
,D/qdlights(  839): set_light_backlight: 43
,D/qdlights(  839): set_light_backlight: 40
,D/qdlights(  839): set_light_backlight: 37
,D/qdlights(  839): set_light_backlight: 33
,D/qdlights(  839): set_light_backlight: 30
,D/qdlights(  839): set_light_backlight: 27
,D/qdlights(  839): set_light_backlight: 23
,D/qdlights(  839): set_light_backlight: 20
,D/qdlights(  839): set_light_backlight: 17
,D/qdlights(  839): set_light_backlight: 13
,D/qdlights(  839): set_light_backlight: 10
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 153769139528; DSPS: 5137240; Offset : -3008741928
,I/PowerManagerService(  839): ALS enabled for SRE
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34198 ms ago)
I/PowerManagerService(  839): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  839): ALS enabled for SRE
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34207 ms ago)
W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  839): Sleeping (uid 1000)...
D/LPWGController(  839): [updateScreenState] screen on = false
,D/LPWGController(  839): disable proximity sensor
D/LPWGController(  839): enable proximity sensor
I/SensorManager(  839): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@30195008] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  839): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  839): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  839): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  839): activate: handle is 48, enable
V/sensors_hal_Ctx(  839): activate sensors is 1400000000000
D/sensors_hal_Thresh(  839): enable: handle=48
I/sensors_hal_SAM(  839): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  839): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  839): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  839): enable: Received response: 0
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34266 ms ago)
I/Adreno-EGL(  839): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  839): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  839): Build Date: 03/02/15 Mon
I/Adreno-EGL(  839): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  839): Remote Branch: 
I/Adreno-EGL(  839): Local Patches: 
I/Adreno-EGL(  839): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1053 us)
,I/Sensors (  418): sns_pwr.c(273):acquiring wakelock
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
I/ActivityManager(  839): Process com.google.android.talk (pid 7591) has died
D/LPWGController(  839): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  839): current mode = 1  value = 1 1
I/LPWGController(  839): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  839): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  839): set_light_backlight: 0
,I/SensorManager(  839): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  839): activate: handle is 46, disable
V/sensors_hal_Ctx(  839): activate sensors is 1000000000000
D/sensors_hal_LP2(  839): enable: handle=46
D/sensors_hal_LP2(  839): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  839): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  839): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  839): Display changed displayId=0
,V/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  839): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1750): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  839): Excessive delay in setPowerMode(): 191ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  839): Got set_interactive hint
D/KeyguardViewMediator( 1370): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1331): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1370): notifyScreenOffLocked
D/SmartCoverViewMediator( 1331): notifyScreenOffLocked
D/SmartCoverViewMediator( 1331): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1370): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1370): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1370): unregisterProximitySensor
,D/StatusBarWindowView( 1370): onScreenTurnedOff why = 3
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/WifiServerServiceExt(  839): sendKtScanInterval  mRtspPlay : false
,I/WifiServerServiceExt(  839): set CMD_KT_SCAN_INTERVAL
V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=on, calling pid 839
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: enter: screen_state=on
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
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/GpsLocationProvider(  839): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
,D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): updateLightsLocked : turn off led
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1804): RESTART MSG
D/SplitWindow(  839): check instance of lgWin Window{13979d87 u0 SearchPanel}
,D/LNfcService( 1787): action : android.intent.action.SCREEN_ON
,I/art     (  839): Explicit concurrent mark sweep GC freed 48880(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 2.764ms total 166.993ms
,D/InputDispatcher(  839): Window went away: Window{1fac8c66 u0 SearchPanel}
I/[SystemUI]Clock( 1370): onReceive = android.intent.action.SCREEN_ON
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
I/LgeClockWidgetControlView( 1370): time changed, timezoneChanged : false
,D/Ulp_jni (  839): JNI:system_update. Event-0
,I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1804): lockStatus = 0
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2672): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:54:19
,D/WeatherService( 2672): 2 : ACTION screen on
D/WeatherService( 2672): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2672): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2672): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:54:19
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): ACTION_SCREEN_ON
D/AppCleanupService( 4060): android.intent.action.SCREEN_ON
,V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=off, calling pid 839
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
D/WifiController(  839): CMD_SCREEN_OFF 
D/WifiController(  839): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  839): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1804): clear
I/LEDService( 1804): updateLightsLocked : turn on led
E/LEDService( 1804): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1804): Can't handle this request of patternId:0
D/LEDHandler( 1804): RESTART MSG
D/LNfcService( 1787): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1787): mScreenState : 1, mInProvisionMode : false
,I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2672): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:54:19
D/WeatherService( 2672): 2 : ACTION screen off
D/WeatherService( 2672): 2 : TimeTick Receiver Unregister
D/WeatherService( 2672): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:54:19
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): ACTION_SCREEN_OFF
D/AppCleanupService( 4060): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4060): AppUsageStatsSaveTask
,E/NxpNfcJni( 1787): getReconnectState = 0x0
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
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
,I/Sensors (  418): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1370): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{26f764b4 type 2 when 160128 com.android.systemui} when 160128
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1750): getCallState : 0
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1370): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1370): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 173769969937; DSPS: 5792627; Offset : -3008737369
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{f3ce8dd type 2 when 185905 com.google.android.gms} when 185905
,I/PhenotypeConfigurator( 1731): Scheduling Phenotype for one-off execution 772 seconds from now (1453125290317)
,D/GetConfigurationSnapshotOperation( 1731): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1731): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1731): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 1731): propertyValue:false
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2026): Disconnected process message: 10, size: 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{38eec34d type 2 when 192667 android} when 192667
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 193770763107; DSPS: 6448013; Offset : -3008736041
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ClearcutLoggerApiImpl( 1731): disconnect managed GoogleApiClient
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 213771437057; DSPS: 7103395; Offset : -3008733192
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2026): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
D/HeadsetStateMachine( 2026): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 233772203613; DSPS: 7758780; Offset : -3008729913
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2026): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 253772877667; DSPS: 8414162; Offset : -3008727090
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 273773554586; DSPS: 9069544; Offset : -3008721271
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 293774322964; DSPS: 9724930; Offset : -3008746481
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
D/HeadsetStateMachine( 2026): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,D/HeadsetStateMachine( 2026): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  839): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2026): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 313775075977; DSPS: 10380314; Offset : -3008726490
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/HeadsetStateMachine( 2026): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 333775736335; DSPS: 11035696; Offset : -3008737179
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6418): --= Surplus to requirements =--
I/jxcore-log( 6418): 
,I/jxcore-log( 6418): ****TEST TOOK:  ms ****
I/jxcore-log( 6418): 
I/jxcore-log( 6418): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6418): 
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/AndroidRuntime( 8050): 
D/AndroidRuntime( 8050): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8050): CheckJNI is OFF
,D/AndroidRuntime( 8050): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  839): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  839): Killing 6418:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,I/WindowState(  839): WIN DEATH: Window{344eb02a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  839): Focus left window: Window{344eb02a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  839): Window went away: Window{344eb02a u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  839): Skipping PackageSetting{3c1a04a9 com.example.hello/10317} due to missing metadata
,I/ActivityManager(  839):   Force finishing activity ActivityRecord{17d94e28 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  839): Display changed displayId=0
,D/DSDPConnection( 1750): Display #0 changed.
W/ActivityManager(  839): Spurious death for ProcessRecord{17b8ce02 6418:com.test.thalitest/u0a316}, curProc for 6418: null
,I/ActivityManager(  839): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
W/GeofencerStateMachine( 1731): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
,I/art     ( 1941): Explicit concurrent mark sweep GC freed 9355(546KB) AllocSpace objects, 3(71KB) LOS objects, 39% free, 12MB/21MB, paused 11.974ms total 135.071ms
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8074 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/System.err( 3620): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 3620): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3620): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3620): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3620): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3620): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3620): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3620): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3620): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3620): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3620): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3620): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 4240): Explicit concurrent mark sweep GC freed 4194(230KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 14MB/18MB, paused 751us total 169.687ms
,W/SQLiteConnectionPool( 4240): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/[LGHome]EVENT( 1878): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_REMOVED
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
I/Activity( 1878): Activity.onPostResume() called 
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
,W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
,W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1370): handleShortcutListChanged...
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
,W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
,I/SystemUI[Framework](  839): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  839): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  839): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  839): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SystemUI[Framework](  839): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@204dda43,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/SystemUI[Framework](  839): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  839): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  839): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  839): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@204dda43,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/InputDispatcher(  839): Focus entered window: Window{36a42b18 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
,D/KeyguardModel( 1370): handleShortcutListChanged...
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
I/art     (  839): Explicit concurrent mark sweep GC freed 32326(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/34MB, paused 5.710ms total 279.934ms
I/art     (  839): WaitForGcToComplete blocked for 261.552ms for cause Explicit
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
W/ResourcesManager( 8074): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8074): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8074): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 8074): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/administrator(  839): Handling package changes for user 0
D/LGEmail ( 8074): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/art     (  839): Explicit concurrent mark sweep GC freed 4134(239KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.428ms total 214.750ms
,W/InputMethodManagerService(  839): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  839): Got RemoteException sending setActive(false) notification to pid 6418 uid 10316
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/Timeline(  839): Timeline: Activity_windows_visible id: ActivityRecord{15e82bff u0 com.lge.launcher2/.Launcher t221} time:340713
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/PackageChangeReceiver( 8074): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1618): Unable to connect to the editor to retrieve text... will retry later
D/AndroidRuntime( 8050): Shutting down VM
,I/NotificationService(  839): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/AppUp4:PreloadHelper( 7522): added Exclude : com.test.thalitest
D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  839): Receieved: android.intent.action.PACKAGE_REMOVED
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,W/IInputConnectionWrapper( 1878): getTextAfterCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  839): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8107 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
D/TaskPersister(  839): removeObsoleteFile: deleting file=222_task.xml
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager(  839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager( 8107): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8107): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8107): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8107): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8107): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
E/SharedPreferencesImpl( 1878): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
I/Timeline( 1878): Timeline: Activity_idle id: android.os.BinderProxy@2aecf135 time:341290

```
