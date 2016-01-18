#### Test 56151093b6ab50f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/sensors_hal_Time(  955): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  955): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  955): tsOffsetIs: Apps: 94853795541; DSPS: 3206625; Offset : -3015090679
,D/AndroidRuntime( 6304): 
D/AndroidRuntime( 6304): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6304): CheckJNI is OFF
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/GAV2    ( 6075): Thread[GAThread,5,main]: No campaign data found.
D/Finsky  ( 5817): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
--------- beginning of system
V/AlarmManager(  955): RTC_WAKEUP set : Alarm{67c8dcf type 0 when 1453102497164 com.android.vending} when 1453102497164
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 6304): Calling main entry com.android.commands.am.Am
I/NotificationManager(  955): android: cancelAsUser(2) by android
I/ActivityManager(  955): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  955): setTaskToReturnTo : TaskRecord{19385d1d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  955): setTaskToReturnTo : TaskRecord{19385d1d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  955): AppWindowTokenEx init.. 
D/ContextHelper(  955): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  955): Focus left window: Window{c2699d3 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6304): Shutting down VM
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  955): check instance of lgWin Window{1d8288bf u0 Starting com.test.thalitest}
I/ActivityManager(  955): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6332 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/ActivityManager(  955): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6349 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1942): Closing mic
,I/GservicesProvider( 6332): Gservices pushing to system: true; secure/global: true
I/MicrophoneInputStream( 1942): mic_close com.google.android.apps.gsa.speech.audio.u@c596074
,V/AudioRecord( 1942): stop()
D/AudioRecord( 1942): AudioRecord->stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
I/WindowStateAnimator(  955): Starting window displayed
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
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb42a5000
,I/SystemUI[Framework](  955): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/audio_hw_primary(  279): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
W/PhoneWindowManagerEx(  955): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  955): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  955): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  955): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@d1210f6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  955): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1379): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1379): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1379):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1379): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/BarTransitions( 1379): draw background and invalidate : color = 7000000
D/BarTransitions( 1379): draw background and invalidate : color = a090909
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
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb42a5000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioRecord( 1942): stop()
,V/AudioRecord( 1942): stop()
V/AudioRecord( 1942): stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 17
V/AudioPolicyManager(  279): closeInput(17)
V/AudioFlinger(  279): closeInput() 17
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1942): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): ThreadBase::exit
V/AudioSystem( 1972): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): RecordThread 0xb42a5000 exiting
V/AudioSystem( 2682): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb40367a0)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioSystem(  955): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1379): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): releasing 16 from 1942 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/AudioSystem( 1753): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3240): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  279): removeClient_l() pid 1942, calling pid 279
I/GoogleHttpClient( 6332): GMS http client unavailable, use old client
,I/HotwordRecognitionRnr( 1942): Stopping hotword detection.
,I/HotwordRecognitionRnr( 1942): Hotword detection finished
I/GoogleHttpClient( 6332): GMS http client unavailable, use old client
,D/ContextHelper( 6349): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/libc-netbsd( 5817): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5817): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5817): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5817): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  272): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 5817): propertyValue:false
D/libc-netbsd( 5817): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5817): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/WebViewFactory( 6349): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6349): Time to load native libraries: 2 ms (timestamps 6326-6328)
I/LibraryLoader( 6349): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6349): Binding Chromium to main looper Looper (main, tid 1) {391d205c}
,I/LibraryLoader( 6349): Expected native library version number "",actual native library version number ""
I/chromium( 6349): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6349): Initializing chromium process, singleProcess=true
,W/art     ( 6349): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6349): ApplicationContext is null in ApplicationStatus
D/libc-netbsd( 5817): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5817): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/chromium( 6349): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6349): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6349): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6349): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6349): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6349): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6349): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6349): Remote Branch: 
I/Adreno-EGL( 6349): Local Patches: 
I/Adreno-EGL( 6349): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AudioPolicyService(  279): registerClient() client 0xb40cab20, uid 10316
,D/BluetoothManagerService(  955): Message: 20
,D/BluetoothManagerService(  955): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a9fffbc:true
D/BluetoothAdapterService(512353864)( 1972): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31523de
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  955): android: cancelAsUser(2) by android
,I/qtaguid ( 5817): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5817): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5817): untagSocket(41) failed with errno -22
D/Finsky  ( 5817): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,W/art     ( 6349): Attempt to remove local handle scope entry from IRT, ignoring
,D/AlertService( 6158): Beginning updateAlertNotification
W/AwContents( 6349): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6349): CordovaWebView is running on device made by: LGE
,I/ActivityManager(  955): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6408 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/art     ( 6349): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6349): Attempt to remove local handle scope entry from IRT, ignoring
D/AlertService( 6158): No fired or scheduled alerts
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 6158): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(2) by com.android.calendar
,I/NotificationManager( 6158): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager(  955): android: cancelAsUser(2) by android
I/NotificationManager( 6158): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(15) by com.android.calendar
,I/NotificationManager( 6158): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6158): com.android.calendar: cancel(20) by com.android.calendar
,D/AlertService( 6158): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/Activity( 6349): Activity.onPostResume() called 
D/OpenGLRenderer( 6349): Render dirty regions requested: true
I/OpenGLRenderer( 6349): Initialized EGL, version 1.4
,D/AlarmScheduler( 6158): No events found starting within 1 week.
I/ActivityManager(  955): Killing 6158:com.android.calendar/u0a13 (adj 15): empty #11
D/OpenGLRenderer( 6349): Enabling debug mode 0
W/ResourcesManager( 6408): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6408): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Atlas   ( 6349): Validating map...
,D/SplitWindow(  955): check instance of lgWin Window{2bd3e025 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/libprocessgroup(  955): failed to open /acct/uid_10013/pid_6158/cgroup.procs: No such file or directory
,W/chromium( 6349): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/ActivityManager(  955): Killing 5939:com.google.android.talk/u0a61 (adj 15): empty #11
I/MultiDex( 6408): VM with version 2.1.0 has multidex support
I/MultiDex( 6408): install
I/MultiDex( 6408): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  955): failed to open /acct/uid_10061/pid_5939/cgroup.procs: No such file or directory
,V/JNIHelp ( 6408): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/InputDispatcher(  955): Focus entered window: Window{2bd3e025 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputMethodManagerService(  955): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  955): Displayed com.test.thalitest/.MainActivity: +1s262ms
,I/Timeline(  955): Timeline: Activity_windows_visible id: ActivityRecord{accab92 u0 com.test.thalitest/.MainActivity t222} time:97140
I/Timeline( 6349): Timeline: Activity_idle id: android.os.BinderProxy@146892db time:97145
W/ActivityThread( 6408): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6408): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1483e93e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6408): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6408): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6408): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1735): callingUid 10006, callindPid: 1735
,E/MDM     ( 1735): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 6408): Reading stored module config
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4432): Restart initialization of location
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
W/BindingManager( 6349): Cannot call determinedVisibility() - never saw a connection for the pid: 6349
,W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,D/ChimeraCfgMgr( 6408): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/qtaguid ( 5817): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5817): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5817): untagSocket(41) failed with errno -22
D/CAR.SERVICE( 6408): Connecting to CarCallService...
,I/art     ( 6408): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6408): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6408): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6408): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6408): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6408): Creating a new PhoneAdapter instance
W/ActivityManager(  955): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6408): setListener: com.google.android.gms.car.dn@1e611925
W/ActivityManager(  955): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6408): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6408): Starting CarCallService with initial phone null
I/NotificationManager( 6408): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/art     ( 6408): CheckpointMarkThreadRoots callback created = 0xb042d590
,I/art     ( 6408): CheckpointMarkThreadRoots callback created = 0xb042d580
,D/CAR.SERVICE( 6408): Package validated; name: com.android.vending
,I/NotificationManager( 5817): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5817): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/art     ( 5817): CheckpointMarkThreadRoots callback created = 0xaaff3ba0
,I/art     ( 5817): CheckpointMarkThreadRoots callback created = 0xaaff3b60
,D/JsMessageQueue( 6349): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6349): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622862336
D/JX-Cordova( 6349): jxcore cordova android initializing
,I/art     ( 6349): CheckpointMarkThreadRoots callback created = 0x9b2084e0
,I/art     ( 6349): CheckpointMarkThreadRoots callback created = 0x9b2084b0
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/PowerManagerServiceEx(  955): acquireWakeLockInternal: lock=335319980, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=955
D/WeatherService( 2661): 2 : TimeTick Intent has been received, Time(hour:min:sec) 8:35:0
,D/WeatherService( 2661): 2 : TimeTick Intent And Screen On
D/WeatherService( 2661): 2 : SDK version : 21
W/ActivityManager(  955): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2661): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2661): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2661): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2661): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2661): 2 : This is isUpdating : false
D/WeatherService( 2661): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2661): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2661): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2661): 2 : Fixed theme : optimus
,D/WeatherReflect( 2661): 2 : Map key string is -2
D/lim     ( 2661): 2 : time = 08:35
I/WeatherReflect( 2661): Model Name : LG-D722
,D/WeatherTheme( 2661): 2 : Different view - status_min_formatted : 34 != 35
D/WeatherTheme( 2661): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2661): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2661): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2661): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2661): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2661): forecast size is 0
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2661): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2661): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2661): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2661): url is : null
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2661): 2 : update view, appWidgetId: 2
D/WeatherService( 2661): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 8:35:0
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PowerManagerServiceEx(  955): releaseWakeLockInternal: lock=335319980 [*alarm*], flags=0x0
,I/NotificationManager(  955): android: cancelAsUser(2) by android
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/qtaguid ( 5817): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5817): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5817): untagSocket(41) failed with errno -22
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
,I/[SystemUI]Clock( 1379): called onTimeUpdated()
I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/art     (  955): Explicit concurrent mark sweep GC freed 32854(1598KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.752ms total 219.689ms
,W/ResourcesManager( 5817): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5817): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5817): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5817): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  955): RTC_WAKEUP set : Alarm{37a11fbd type 0 when 1453102500625 com.android.vending} when 1453102500625
,D/Finsky  ( 5817): [704] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1735): client connected with version: 8296000
D/Finsky  ( 5817): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5817): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  955): Process com.android.contacts (pid 6028) has died
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  955): android: cancelAsUser(2) by android
,D/libc-netbsd( 5817): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5817): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5817): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5817): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  272): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 5817): propertyValue:false
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  955): Process com.google.android.gm (pid 6075) has died
,W/jxcore-log( 6349): Initializing JXcore engine
,W/jxcore-log( 6349): JXcore engine is ready
W/jxcore-log( 6349): Starting JXcore engine
,W/.test.thalitest( 6349): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6291]" dev="sockfs" ino=6291 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6349): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3091 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6349): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6460]" dev="sockfs" ino=6460 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6349): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6349): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6349): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30224]" dev="sockfs" ino=30224 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/ActivityManager(  955): Process com.android.gallery3d (pid 6219) has died
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  955): Process com.lge.lockscreensettings (pid 6047) has died
,W/jxcore-log( 6349): Platform android
W/jxcore-log( 6349): 
W/jxcore-log( 6349): Process ARCH arm
W/jxcore-log( 6349): 
,V/AlarmManager(  955): RTC_WAKEUP set : Alarm{3b67d97b type 0 when 1453102502626 com.google.android.googlequicksearchbox} when 1453102502626
,I/jxcore-log( 6349): JXcore Cordova bridge is ready!
I/jxcore-log( 6349): 
W/jxcore-log( 6349): JXcore engine is started
,I/chromium( 6349): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 6349): Toggling radios to true
I/jxcore-log( 6349): 
,D/BluetoothAdapter( 6349): enable(): BT is already enabled..!
D/WifiServiceImplEx(  955): setWifiEnabled: true pid=6349, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  955): setWifiEnabled: true pid=6349, uid=10316
D/WifiServiceImplEx(  955): disconnect pid=6349, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  955): reconnect pid=6349, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6349): Radios toggled
I/jxcore-log( 6349): 
I/jxcore-log( 6349): My device name is: LGE-LG-D722
I/jxcore-log( 6349): 
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2795): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/wpa_supplicant( 2795): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
,E/WifiStateMachine(  955): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1805): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,E/WifiConfigStore(  955): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  955): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  955): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  955): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  272): Clearing all IP addresses on wlan0
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 7
,V/NativeCrypto( 1735): Read error: ssl=0xb044ce00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1735): SSL shutdown failed: ssl=0xb044ce00: I/O error during system call, Broken pipe
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/WifiHS20(  955): hidePasspointNotification off =false
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:03.515 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  955): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  955): ignoring duplicate network state non-change
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  955): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  955): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): ValidatedState{ when=-5ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): DefaultState{ when=-15ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): Forcing reevaluation
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/ActivityManager(  955): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6498 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/WifiHS20(  955): hidePasspointNotification off =false
E/WifiStateMachine(  955): Start Disconnecting Watchdog 1
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  955): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  955): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2795): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:03.596 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
D/CommandListener(  272): Clearing all IP addresses on wlan0
,D/ConnectivityService(  955): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  955): disableDataServiceNotify
D/WifiHS20(  955): hidePasspointNotification off =false
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
D/DSQN    (  955): stop dsqn bin
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:03.638 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
D/WifiNetworkAgent(  955): NetworkAgent: NetworkAgent channel lost
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:03.654 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:03.658 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  955): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  955):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  955):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiHS20(  955): hidePasspointNotification off =false
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  955): SUPPLICANT_STATE_CHANGED_ACTION
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiServerServiceExt(  955): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt(  955): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  955): setSupplicantStateSCANNING
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
,D/ConnectivityService(  955): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  955): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1379): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): Disconnected - quitting
D/CSLegacyTypeTracker(  955): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  955): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  955): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  955): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  955): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  955): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  955): MasterInitialState.processMessage what=3
D/ConnectivityService(  955): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  955): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/QCNEJ   ( 1835): |CORE| No family connected
W/QCNEJ   ( 1835): |CORE| No family connected
D/WIFI    (  955): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  955):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/QCNEJ   ( 1835): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/Tethering(  955): MasterInitialState.processMessage what=3
V/NetworkPolicy(  955): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  955): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkManagementService(  955): Removing idletimer
D/DhcpStateMachine(  955): StoppedState
D/DhcpStateMachine(  955): StoppedState{ when=-104ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1835): |CORE| sendDefaultNwMsg: default = -1
W/Settings(  955): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TelephonyNetworkFactory-1( 1753): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1379): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1379): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1379): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1379): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/charger_monitor(  488): init target 500000
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/WifiController(  955): battery changed pluggedType: 2
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
D/charger_monitor(  488): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  955): battery changed pluggedType: 2
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/ResourcesManager( 6498): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6498): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6498): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6498): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 6498): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6498): Using schema version: 115
,I/IndexDatabaseHelper( 6498): Index is fine
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
I/ActivityManager(  955): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6525 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/CAR.SERVICE( 6408): mConnectedToCar = false, abort
,I/PCSuite ( 6525): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6525): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6525): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/ActivityThread( 6408): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2719a633 that was originally bound here
E/ActivityThread( 6408): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2719a633 that was originally bound here
E/ActivityThread( 6408): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6408): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6408): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6408): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6408): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6408): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6408): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6408): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6408): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6408): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6408): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6408): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6408): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6408): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6408): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6408): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6408): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6408): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6408): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6408): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6408): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6408): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6408): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2c98891c that was originally bound here
E/ActivityThread( 6408): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2c98891c that was originally bound here
E/ActivityThread( 6408): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6408): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6408): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6408): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6408): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6408): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6408): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6408): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6408): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6408): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6408): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6408): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6408): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6408): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6408): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6408): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6408): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6408): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6408): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6408): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6408): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  955): Unbind failed: could not find connection for android.os.BinderProxy@1f9d4398
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
I/PCSuite ( 6525): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6525): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6525): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  955): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6547 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.672ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.403ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 21.120ms
,I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2795): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/LocSvc_java(  955): onReceive
,I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:04.754 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = false, mWifiLevel = 0
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:04.761 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  955): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  955): setSupplicantStateASSOCIATING
,I/wpa_supplicant( 2795): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
D/WifiServerServiceExt(  955): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  955): setSupplicantStateASSOCIATED
W/ResourcesManager( 6547): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:04.799 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:04.8 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = false, mWifiLevel = 0
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  955): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  955): setSupplicantStateFOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2795): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2795): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  955): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  955): setSupplicantStateGROUP_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1379): Got a,ction android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
,I/WifiServiceExtension(  955): setVHTCapabilityType  : false
I/WifiServerServiceExt(  955): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  955): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  955): setSecurityType  : 2
,I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:04.853 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:04.856 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
D/ConnectivityService(  955): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: ,null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  955): Got NetworkAgent Messenger
D/ConnectivityService(  955): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  955): NetworkAgent connected
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
E/WifiConfigStore(  955): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  955): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  272): Setting iface cfg
E/WifiStateMachine(  955): Start Dhcp Watchdog 2
D/DhcpStateMachine(  955): StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  955): WaitBeforeStartState
D/ConnectivityService(  955): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt(  955): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  955): setSupplicantStateCOMPLETED
,D/WifiServerServiceExt(  955): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  955): setSupplicantStateCOMPLETED
,E/WifiStateMachine(  955): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  955): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  955): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@bd47625 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  955): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@bd47625 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  955): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  955): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  955): DHCP Start wake lock is acquired.
D/CommandListener(  272): Setting iface cfg
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  272): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper(  955): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/ConnectivityService(  955): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  955): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  955): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  955): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine(  955): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  955): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService(  955): ignoring duplicate network state non-change
D/ConnectivityService(  955): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  955): Adding iface wlan0 to network 101
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:05.037 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
,E/ConnectivityService(  955): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  955): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  955): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  272): netlink response contains error (File exists)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  955): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  955): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  955): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  955): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:05.049 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = false, mWifiLevel = 0
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
D/WifiHS20(  955): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:05.064 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = true, mWifiLevel = 2
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/WifiHS20(  955): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:05.075 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
D/Nat464Xlat(  955): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  955): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  955): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  955): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  955):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  955):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  955):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  955):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  955):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  955): currentScore = 0, newScore = 20
D/ConnectivityService(  955):    accepting network in place of null
D/ConnectivityService(  955): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  955): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  955): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} ,explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  955): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/WIFI    (  955):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  955): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1753): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  955): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  955): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  955): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  955): MasterInitialState.processMessage what=3
D/ConnectivityService(  955): validation of new default Network = false
D/ConnectivityService(  955): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  955): enableDataServiceNotify 
D/DSQN    (  955): start dsqn bin
W/QCNEJ   ( 1835): |CORE| No family connected
I/QCNEJ   ( 1835): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): [LWD] Start DNSResolver start to wait
I/QCNEJ   ( 1835): |CORE| sendDefaultNwMsg: default = 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): [LWD] wait 500ms before dns check
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): mWifiConnected = true, mWifiLevel = 2
V/NetworkPolicy(  955): [LG_RESTRICTED] checkMobilePolicy_type()
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at null
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1379): Remote
,D/ConnectivityService(  955): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  955):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  955):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  955): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1379): CM callback handler got msg 524290
I/DSQN    ( 6577): DSQN samuel.seo ver 141203
E/DSQN    ( 6577): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6577): created command queue thread
I/DSQN    ( 6577): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6577): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/TelephonyIcons( 1379): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1379): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/Babel_SMS( 6547): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6547): MmsConfig.loadMmsSettings
I/Babel_SMS( 6547): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6547): MmsConfig.loadFromDatabase
D/DhcpStateMachine(  955): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  955): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  955): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6586): version 5.5.6 starting
,E/dhcpcd  ( 6586): get_duid: Read-only file system
W/art     ( 6547): Suspending all threads took: 5.116ms
,E/Babel_SMS( 6547): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6547): MmsConfig.loadFromResources
E/Babel_SMS( 6547): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6547): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6547): CheckpointMarkThreadRoots callback created = 0xb042d7d0
I/dhcpcd  ( 6586): wlan0: rebinding lease of 192.168.1.134
,D/SensorManager( 6547): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6547): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6547): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6547): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6547): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6547): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6547): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6547): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6547): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6547): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6547): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6547): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6547): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6547): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6547): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6547): found sensor: Motion Accel, handle=46
I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/art     ( 6547): CheckpointMarkThreadRoots callback created = 0xb042d7c0
I/ActivityManager(  955): Process com.google.android.apps.plus (pid 5756) has died
,W/Settings( 6547): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6547): startup - clean
,I/dhcpcd  ( 6586): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  270): 
I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/dhcpcd  ( 6586): wlan0: leased 192.168.1.134 for 86400 seconds
I/Babel   ( 6547): deleted: false for 0
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
I/PCSuite ( 6525): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6525): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6525): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
I/PCSuite ( 6525): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6525): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6525): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6547): Unsupported mime audio/x-lg-flac
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6547): Unsupported mime audio/adpcm
W/AudioCapabilities( 6547): Unsupported mime audio/g726
D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
W/AudioCapabilities( 6547): Unsupported mime audio/x-ms-wma
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6498): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6547): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6547): Unsupported mime video/mjpg
D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): [LWD] DNSResolver start dns
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
W/art     ( 6547): Suspending all threads took: 9.249ms
W/VideoCapabilities( 6547): Unsupported mime video/theora
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
W/AudioCapabilities( 6547): Unsupported mime audio/evrc
W/AudioCapabilities( 6547): Unsupported mime audio/qcelp
W/VideoCapabilities( 6547): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6547): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6547): Unsupported mime audio/qcelp
W/AudioCapabilities( 6547): Unsupported mime audio/evrc
D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
W/VideoCapabilities( 6547): Unsupported mime video/mp4v-esdp
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
,I/PCSuite ( 6525): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
I/VideoCapabilities( 6547): Unsupported profile 4 for video/mp4v-es
,D/PCSuite ( 6525): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
W/VideoCapabilities( 6547): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
W/VideoCapabilities( 6547): Unrecognized profile 2130706433 for video/avc
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  955): DHCPV4 succeeded on wlan0
W/VideoCapabilities( 6547): Unrecognized profile 2130706433 for video/avc
D/LgDhcpStateMachineHelper(  955): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  955): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/PCSuite ( 6525): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/LgDhcpStateMachineHelper(  955): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  955): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  955): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  955): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  955): DHCP Start/Renew wake lock is released.
D/PCSuite ( 6525): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/DhcpStateMachine(  955): RunningState
,W/VideoCapabilities( 6547): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6547): onServiceConnected
,W/Babel   ( 6547): Attempted to change video mute state without an active call.
I/NotificationManager( 6547): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out(  955): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 6577): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6577): restart monitoring
D/LGDataListener(  272): argv[0]=dsqncommand
,D/LGDataListener(  272): argv[1]=wlan0
D/LGDataListener(  272): argv[2]=1
D/LGDataListener(  272): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6577): dsqn report finish
D/DSQN    (  955): DSQM DsqnNotification wlan0  1
D/DSQN    (  955): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 07:35:05 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453102505920], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453102505900]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  955): Validated
D/ConnectivityService(  955): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  955): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  955):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  955):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  955):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  955): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  955): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  955):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  955):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  955): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  955): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  955): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  955): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  955):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1379): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1753): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  955): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  955): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1379): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1379): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  955): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  955): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  955): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/ActivityManager(  955): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6626 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider(  955): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  955): onReceive
D/LocSvc_java(  955): got connectivity action
,I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  955): broadcast - no network connections
D/LocSvc_java(  955): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  955): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  955): onReceive
D/LocSvc_java(  955): got connectivity action
D/LocSvc_java(  955): broadcast - no network connections
D/LocSvc_java(  955): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  955): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  955): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  955): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  955): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  955): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  955): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:06.867 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  955): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  955): identical MTU - not setting
D/Nat464Xlat(  955): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  955): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  955):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  955):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  955): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  955): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  955): enableDataServiceNotify 
D/DSQN    (  955): start dsqn bin
D/DSQN    (  955): dsqn is running restart
,D/ConnectivityManager.CallbackHandler( 1379): CM callback handler got msg 524295
I/DSQN    ( 6654): DSQN samuel.seo ver 141203
E/DSQN    ( 6654): DSQN sock connect success to lgdatalistenerd
,I/DSQN    ( 6654): created command queue thread
I/DSQN    ( 6654): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6654): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/MusicStore( 6626): Database version: 120
,E/lowmemorykiller(  242): Error writing /proc/5817/oom_score_adj; errno=22
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6626): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  955): Process com.android.vending (pid 5817) has died
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6626): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6626): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6626): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6626): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6626): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6626): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1394f611: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6626): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6626): GMSCore installation verified
I/ConfigStore( 6626): Config Database version: 1
,I/MediaRouter( 6626): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6626): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6626): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6626): type=WIFI subType= reason=null isConnected=true
,I/NotificationManager( 1942): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ActivityManager(  955): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6674 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/AlarmManager(  955): ELAPSED_WAKEUP set : Alarm{111d7e6e type 2 when 106325 com.google.android.gms} when 106325
,I/GHttpClientFactory( 6626): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 08:35:07.913 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/GoogleURLConnFactory( 6626): Using platform SSLCertificateSocketFactory
I/NotificationManager( 6626): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6674): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6674): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6674): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/WifiInternetCheck(  955): Single check msg out of sync, ignoring.
,D/ConnectivityService(  955): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  955): Process com.google.android.talk (pid 6547) has died
,D/GpsLocationProvider(  955): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  955): onReceive
D/LocSvc_java(  955): got connectivity action
D/LocSvc_java(  955): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  955): Sending msg: 4 arg1:1 arg2:1
I/[SystemUI]QuickSettingsHandler( 1379): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/NetworkMonitor( 6626): type=WIFI subType= reason=null isConnected=true
D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  955): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  955): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/LGEmail ( 6674): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6674): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/jxcore-log( 6349): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6349): 
D/eas_req ( 6674): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  955): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6705 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6674): JNI_OnLoad()
I/HubEmail( 6674): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6674): registerNatives()
I/HubEmail( 6674): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6674): registerNativeMethods()
I/HubEmail( 6674): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6674): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6674): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6705): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6705): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6705): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6705): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6705): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6705): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6705): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6705): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  955): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6731 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6705): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6705): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6705): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6705): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6705): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6705): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  955): Killing 6260:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  955): failed to open /acct/uid_10014/pid_6260/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6731): onCreate
W/AppUp4:DB( 6731):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6731):  setFingerPrint start
I/AppUp4:DB( 6731):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6731):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6731):  SDK version = 0
I/AppUp4:DB( 6731):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6731): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6731): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6731): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6731): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6731): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6731): onReceive
I/AppUp4:CustModeStarterReceiver( 6731): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6731): Context : android.app.ReceiverRestrictedContext@146aff65
D/AppUp4:CustFacade( 6731): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6731): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6731): begin check event
,I/AppUp4:CustModeStarterReceiver( 6731): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6731): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6731): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6731): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6731): handleAsyncCustNotification do not startCustService
I/ActivityManager(  955): Killing 6408:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/SQLiteConnectionPool( 4432): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/libprocessgroup(  955): failed to open /acct/uid_10006/pid_6408/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3240): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3240): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3240): networkInfo.isConnected() = false
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  955): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6755 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/jxcore-log( 6349): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6349): 
,I/jxcore-log( 6349): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6349): 
D/PhoneMonitor( 6755): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6755): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6755): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  955): Killing 6498:com.android.settings/1000 (adj 15): empty #11
I/jxcore-log( 6349): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6349): 
I/jxcore-log( 6349): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6349): 
,D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
I/jxcore-log( 6349): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6349): 
I/jxcore-log( 6349): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6349): 
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out(  955): propertyValue:false
,D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out(  955): propertyValue:false
I/DSQN    ( 6654): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6654): restart monitoring
,I/DSQN    ( 6654): dsqn report finish
D/LGDataListener(  272): argv[0]=dsqncommand
D/LGDataListener(  272): argv[1]=wlan0
D/LGDataListener(  272): argv[2]=1
D/LGDataListener(  272): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  955): DSQM DsqnNotification wlan0  1
D/DSQN    (  955): start to monitor internet connection
W/libprocessgroup(  955): failed to open /acct/uid_1000/pid_6498/cgroup.procs: No such file or directory
,I/CheckinService( 4432): Checkin interval check for package: unspecified last checkin: 1453102482665 min interval config: 0 actual interval: 26725
V/DownloadManager( 3294): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3294): DownloadService onCreate
,I/DownloadManager( 3294): in removeSpuriousFiles
I/NotificationManager( 3294): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3294): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3294): created cursor android.database.sqlite.SQLiteCursor@1483e93e on behalf of 3294
D/PhoneMonitor( 6755): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6755): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6755): [parse] Load xml
I/DownloadManager( 3294): in trimDatabase
,V/DownloadManager( 3294): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/TelephonyAutoProfiling( 6755): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6755): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3294): created cursor android.database.sqlite.SQLiteCursor@112f639f on behalf of 3294
,D/PhoneMonitor( 6755): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  955): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6788 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3294): DownloadService onStartCommand
V/DownloadManager( 3294): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3294): created cursor android.database.sqlite.SQLiteCursor@3f515b4a on behalf of 3294
I/CheckinService( 4432): Checking schedule, now: 1453102509488 next: 1453102512623
I/CheckinService( 4432): active receiver: disabled
,V/DownloadManager( 3294): DownloadService onDestroy
,I/ActivityManager(  955): Killing 5914:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5243): android.os.DeadObjectException
,W/System.err( 5243): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5243): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5243): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5243): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5243): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5243): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5243): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5243): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5243): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5243): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5243): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5243): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5243): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5243): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5243): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5243): android.os.DeadObjectException
W/System.err( 5243): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5243): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5243): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5243): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5243): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5243): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5243): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5243): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5243): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5243): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5243): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5243): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5243): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5243): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5243): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
V/WifiInternetCheck(  955): isHttpConnectionAvailable - We got a valid response : 204
,W/libprocessgroup(  955): failed to open /acct/uid_10089/pid_5914/cgroup.procs: No such file or directory
W/ActivityManager(  955): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/WeatherAncestor( 2661): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:35:9
I/ActivityManager(  955): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6817 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UpdateThreadPoolManager( 2661): 2 : This is isUpdating : false
D/WeatherAncestor( 2661): connectivity changed - connection : true
D/Weather_cast( 2661): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2661): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:35:9
,D/WeatherService( 2661): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  955): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6826 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  955): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2661): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2661): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2661): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6817): Quickset Services start...
W/ResourcesManager( 6826): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UEI.SmartControl( 6817): Manufacture = LGE
D/UEI.SmartControl( 6817): File observer start...
E/UEI.SmartControl( 6817): IR Port is disabled: false
D/UEI.SmartControl( 6817): Starting file observer...
D/UEI.SmartControl( 6817): Extracting JNI libs...
D/UEI.SmartControl( 6817): --- this system supports 32-bit or 64-bit only
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/jxcore-log( 6349): Test app app.js loaded
I/jxcore-log( 6349): 
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6349): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6349): BLE advertisement is supported
I/jxcore-log( 6349): 
,I/chromium( 6349): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Babel_SMS( 6826): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6826): MmsConfig.loadMmsSettings
D/UEI.SmartControl( 6817): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6817): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6817): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6817): --- Selecting new region: 2
I/UEI.SmartControl( 6817): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6817): Platform has CIR...
D/UEI.SmartControl( 6817): NO CIR support, need to check package...
I/UEI.SmartControl( 6817): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6817): QS Service created
,E/UEI.SmartControl( 6817): QS start get config
,I/art     ( 6826): CheckpointMarkThreadRoots callback created = 0xb042d510
I/art     ( 6826): CheckpointMarkThreadRoots callback created = 0xb042d500
,D/UEI.SmartControl( 6817): Loading JNI Libs...
,D/UEI.SmartControl( 6817):  configuring local db...
I/art     (  955): Explicit concurrent mark sweep GC freed 82185(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.637ms total 213.416ms
,I/Babel_SMS( 6826): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6826): MmsConfig.loadFromDatabase
D/SensorManager( 6826): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 6826): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6826): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6826): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6826): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6826): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6826): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6826): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6826): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6826): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6826): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6826): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6826): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6826): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6826): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6826): found sensor: Motion Accel, handle=46
E/Babel_SMS( 6826): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6826): MmsConfig.loadFromResources
E/Babel_SMS( 6826): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6826): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/Settings( 6826): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6826): startup - clean
I/Babel   ( 6826): deleted: false for 0
,I/ActivityManager(  955): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6875 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6817):  ---- Has DB8: true
,W/AudioCapabilities( 6826): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6826): Unsupported mime audio/adpcm
D/UEI.SmartControl( 6817): QS start statue = true Error code = 0
D/UEI.SmartControl( 6817): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 6817): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
W/AudioCapabilities( 6826): Unsupported mime audio/g726
W/AudioCapabilities( 6826): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6826): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6826): Unsupported mime video/mjpg
W/VideoCapabilities( 6826): Unsupported mime video/theora
,D/UEI.SmartControl( 6817): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6817): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6817): IrrcClient ++ 
D/irrcClient( 6817): getIrrcService ++ 
D/irrcClient( 6817): getIrrcService -- 
D/irrcClient( 6817): IrrcClient -- 
W/irrc_jni( 6817): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6817): Services init done
D/UEI.SmartControl( 6817): QS Service init finished
I/UEI.SmartControl( 6817): Device manager: loading config....
D/UEI.SmartControl( 6817): QS Service version name: 0.1.73
D/UEI.SmartControl( 6817): QS Service version code: 1073
,D/UEI.SmartControl( 6817): Service requested: Control
W/AudioCapabilities( 6826): Unsupported mime audio/evrc
W/AudioCapabilities( 6826): Unsupported mime audio/qcelp
W/VideoCapabilities( 6826): Unrecognized profile 2130706433 for video/avc
D/UEI.SmartControl( 6817): Config is loaded...
,W/AudioCapabilities( 6826): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6826): Unsupported mime audio/qcelp
W/AudioCapabilities( 6826): Unsupported mime audio/evrc
D/UEI.SmartControl( 6817):  ----- QS SDK is ready!!!
,D/UEI.SmartControl( 6817): Request IControl service: devices are loaded...
I/UEI.SmartControl( 6817): Notify AllClients services are ready: 0
I/ActivityManager(  955): Killing 6525:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6817): -----IControl: 11
D/UEI.SmartControl( 6817): Caller: com.lge.qremote
D/UEI.SmartControl( 6817): ------------ IControl registerCallback...
I/UEI.SmartControl( 6817): Registering callback...
D/UEI.SmartControl( 6817): -----IControl: 19
D/UEI.SmartControl( 6817): Caller: com.lge.qremote
,I/UEI.SmartControl( 6817): Registering Services Ready callback...
I/UEI.SmartControl( 6817): Notify client services are ready...
D/UEI.SmartControl( 6817): -----IControl: 8
D/UEI.SmartControl( 6817): Caller: com.lge.qremote
W/VideoCapabilities( 6826): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6826): Unsupported profile 4 for video/mp4v-es
,W/libprocessgroup(  955): failed to open /acct/uid_1000/pid_6525/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6817): Internal service binding...
W/VideoCapabilities( 6826): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6826): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6826): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6826): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6826): onServiceConnected
W/Babel   ( 6826): Attempted to change video mute state without an active call.
,I/NotificationManager( 6826): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6826): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6826): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6826): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6826): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  272): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 6826): propertyValue:false
I/Babel   ( 6826): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  955): Killing 5243:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  955): failed to open /acct/uid_10106/pid_5243/cgroup.procs: No such file or directory
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6875): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6875): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6875): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6875): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6875):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6875):   adb logcat -s GAv4
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6875): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6875): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6875): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6875): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6875): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6875): Time to load native libraries: 3 ms (timestamps 26-29)
I/LibraryLoader( 6875): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6875): Binding Chromium to main looper Looper (main, tid 1) {91b1dee}
I/LibraryLoader( 6875): Expected native library version number "",actual native library version number ""
I/chromium( 6875): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6875): Initializing chromium process, singleProcess=true
,W/art     ( 6875): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6875): ApplicationContext is null in ApplicationStatus
W/chromium( 6875): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6875): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6875): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6875): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6875): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6875): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6875): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6875): Remote Branch: 
I/Adreno-EGL( 6875): Local Patches: 
I/Adreno-EGL( 6875): Reconstruct Branch: 
V/AudioPolicyService(  279): registerClient() client 0xb57e9560, uid 10079
,W/AudioManagerAndroid( 6875): Requires BLUETOOTH permission
I/NSApplication( 6875): Starting up...
,I/ActivityManager(  955): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6944 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  955): Killing 6626:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  955): failed to open /acct/uid_10081/pid_6626/cgroup.procs: No such file or directory
,I/ActivityManager(  955): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6972 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  955): Killing 6674:com.lge.email/u0a21 (adj 15): empty #11
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.696ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.686ms
,W/libprocessgroup(  955): failed to open /acct/uid_10021/pid_6674/cgroup.procs: No such file or directory
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.592ms
,W/ResourcesManager( 6972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  955): Killing 6705:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  955): failed to open /acct/uid_1000/pid_6705/cgroup.procs: No such file or directory
,I/ActivityManager(  955): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7003 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7003): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7003): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7003): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7003): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7003): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7003): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7003): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/AlarmManager(  955): RTC_WAKEUP set : Alarm{1d8995f2 type 0 when 1453102512623 com.google.android.gms} when 1453102512623
,V/AlarmManager(  955): RTC_WAKEUP set : Alarm{3ca22ac0 type 0 when 1453102513229 com.google.android.googlequicksearchbox} when 1453102513229
W/ActivityThread( 7003): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7003): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1394f611: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7003): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7003): GMSCore installation verified
I/ConfigStore( 7003): Config Database version: 1
,I/MediaRouter( 7003): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7003): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7003): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7003): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  955): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7039 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7003): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7003): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  955): Killing 6731:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 7039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7039): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7039): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  955): failed to open /acct/uid_10011/pid_6731/cgroup.procs: No such file or directory
,I/NotificationManager( 7003): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7039): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7039): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7039): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  955): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7067 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7039): JNI_OnLoad()
I/HubEmail( 7039): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7039): registerNatives()
I/HubEmail( 7039): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7039): registerNativeMethods()
I/HubEmail( 7039): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7039): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  955): Killing 6755:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  955): failed to open /acct/uid_10038/pid_6755/cgroup.procs: No such file or directory
W/Settings( 7039): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/LGDMClient( 7067): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7067): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7067): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7067): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7067): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7067): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  955): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7091 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7067): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7067): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7067): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7067): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7067): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  955): Killing 6788:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  955): failed to open /acct/uid_10051/pid_6788/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7091): onCreate
W/AppUp4:DB( 7091):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7091):  setFingerPrint start
I/AppUp4:DB( 7091):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7091):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7091):  SDK version = 0
I/AppUp4:DB( 7091):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7091): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7091): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7091): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7091): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7091): onReceive
I/AppUp4:CustModeStarterReceiver( 7091): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7091): Context : android.app.ReceiverRestrictedContext@146aff65
D/AppUp4:CustFacade( 7091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7091): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7091): begin check event
I/AppUp4:CustModeStarterReceiver( 7091): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7091): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7091): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7091): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7091): handleAsyncCustNotification do not startCustService
I/ActivityManager(  955): Killing 6817:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  955): failed to open /acct/uid_10089/pid_6817/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3240): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3240): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3240): networkInfo.isConnected() = false
,I/ActivityManager(  955): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7110 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7110): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7110): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7110): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  955): Killing 6826:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  955): failed to open /acct/uid_10061/pid_6826/cgroup.procs: No such file or directory
,V/DownloadManager( 3294): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3294): DownloadService onCreate
I/NotificationManager( 3294): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3294): in removeSpuriousFiles
V/DownloadManager( 3294): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3294): created cursor android.database.sqlite.SQLiteCursor@15f90bd8 on behalf of 3294
,I/DownloadManager( 3294): in trimDatabase
V/DownloadManager( 3294): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3294): created cursor android.database.sqlite.SQLiteCursor@16d1e216 on behalf of 3294
D/PhoneMonitor( 7110): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7110): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7110): [parse] Load xml
,V/TelephonyAutoProfiling( 7110): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7110): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/ActivityManager(  955): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7138 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3294): DownloadService onStartCommand
V/DownloadManager( 3294): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 4432): Checkin interval check for package: unspecified last checkin: 1453102482665 min interval config: 0 actual interval: 31992
,V/DownloadManager( 3294): created cursor android.database.sqlite.SQLiteCursor@2fdf0d84 on behalf of 3294
,D/PhoneMonitor( 7110): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 4432): Checking schedule, now: 1453102514681 next: 1453102512623
I/CheckinService( 4432): active receiver: enabled
,I/CheckinService( 4432): Preparing to send checkin request
I/EventLogService( 4432): Accumulating logs since 1453102474664
,V/DownloadManager( 3294): DownloadService onDestroy
,D/WeatherAncestor( 2661): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:35:14
,D/UpdateThreadPoolManager( 2661): 2 : This is isUpdating : false
D/WeatherAncestor( 2661): connectivity changed - connection : true
D/Weather_cast( 2661): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2661): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:35:14
D/WeatherService( 2661): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/CheckinRequestBuilder( 4432): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  955): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7161 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  955): getTasks: caller 10074 does not hold GET_TASKS; limiting output
E/ActivityThread( 4432): Failed to find provider info for com.google.android.wearable.settings
D/Weather.Utils( 2661): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2661): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2661): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/ActivityManager(  955): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7178 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  955): RTC_WAKEUP set : Alarm{1522def1 type 0 when 1453102514849 com.android.vending} when 1453102514849
I/art     (  955): Explicit concurrent mark sweep GC freed 18847(1046KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.174ms total 164.802ms
,W/ResourcesManager( 7161): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  955): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7201 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/Babel_SMS( 7161): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7161): MmsConfig.loadMmsSettings
I/Babel_SMS( 7161): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7161): MmsConfig.loadFromDatabase
D/Finsky  ( 7178): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/ResourcesManager( 7201): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7201): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Babel_SMS( 7161): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7161): MmsConfig.loadFromResources
E/Babel_SMS( 7161): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7161): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7161): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 7161): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 7161): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7161): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7161): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7161): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7161): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7161): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7161): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7161): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7161): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7161): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7161): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7161): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7161): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7161): found sensor: Motion Accel, handle=46
,W/art     ( 7201): Verification of void com.google.android.gms.common.app.GmsApplication.attachBaseContext(android.content.Context) took 116.158ms
I/MultiDex( 7201): VM with version 2.1.0 has multidex support
I/MultiDex( 7201): install
I/MultiDex( 7201): VM has multidex support, MultiDex support library is disabled.
,W/Settings( 7161): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7161): startup - clean
I/art     ( 7161): CheckpointMarkThreadRoots callback created = 0xb042d480
,I/Babel   ( 7161): deleted: false for 0
,V/JNIHelp ( 7201): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 7161): CheckpointMarkThreadRoots callback created = 0xb042d460
,D/Finsky  ( 7178): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7178): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7178): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7178): com.android.vending: cancel(-1050172287) by com.android.vending
W/AudioCapabilities( 7161): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7161): Unsupported mime audio/adpcm
W/AudioCapabilities( 7161): Unsupported mime audio/g726
W/AudioCapabilities( 7161): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7161): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 7161): Unsupported mime video/mjpg
W/VideoCapabilities( 7161): Unsupported mime video/theora
I/art     ( 6972): CheckpointMarkThreadRoots callback created = 0xb042d480
,V/MusicLeanback( 7003): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
,D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/Ads     ( 7178): Skipping gmscore version check
D/LGDMClient( 7067): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7067): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,I/art     ( 6972): CheckpointMarkThreadRoots callback created = 0xb042d450
W/ContextImpl( 7067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 7091): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7091): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7091): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7091): onReceive
I/AppUp4:CustModeStarterReceiver( 7091): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7091): Context : android.app.ReceiverRestrictedContext@146aff65
D/AppUp4:CustFacade( 7091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7091): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7091): begin check event
I/AppUp4:CustModeStarterReceiver( 7091): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 7067): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LgeMiscReceiver( 3240): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3240): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3240): networkInfo.isConnected() = true
W/Settings( 7039): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LGDMClient( 7067): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/PhoneState( 3240): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 7110): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7110): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3294): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 7067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
W/ActivityThread( 7201): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
V/DownloadManager( 3294): DownloadService onCreate
W/System  ( 7201): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1483e93e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7201): Installed default security provider GmsCore_OpenSSL
I/DownloadManager( 3294): in removeSpuriousFiles
V/DownloadManager( 3294): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 7067): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7067): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7067): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/NotificationManager( 3294): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/LGDMClient( 7067): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/WeatherAncestor( 2661): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:35:15
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
V/DownloadManager( 3294): created cursor android.database.sqlite.SQLiteCursor@3a0209a2 on behalf of 3294
,I/System.out( 1735): propertyValue:false
I/NotificationManager( 7201): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7201): com.google.android.gms: cancel(39789) by com.google.android.gms
D/UpdateThreadPoolManager( 2661): 2 : This is isUpdating : false
W/AudioCapabilities( 7161): Unsupported mime audio/evrc
D/WeatherAncestor( 2661): connectivity changed - connection : true
D/Weather_cast( 2661): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2661): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:35:15
D/WeatherService( 2661): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 3294): in trimDatabase
V/DownloadManager( 3294): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/ActivityManager(  955): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/LGDMClient( 7067): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7067): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3294): created cursor android.database.sqlite.SQLiteCursor@1da1ef69 on behalf of 3294
D/Weather.Utils( 2661): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3294): DownloadService onStartCommand
V/DownloadManager( 3294): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/WeatherService( 2661): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2661): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,V/DownloadManager( 3294): created cursor android.database.sqlite.SQLiteCursor@91b1dee on behalf of 3294
W/AudioCapabilities( 7161): Unsupported mime audio/qcelp
W/VideoCapabilities( 7161): Unrecognized profile 2130706433 for video/avc
D/LGDMClient( 7067): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,V/DownloadManager( 3294): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,W/AudioCapabilities( 7161): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7161): Unsupported mime audio/qcelp
W/AudioCapabilities( 7161): Unsupported mime audio/evrc
,V/DownloadManager( 3294): created cursor android.database.sqlite.SQLiteCursor@37be728f on behalf of 7178
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Finsky  ( 7178): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7178): [1] Libraries$2.run: Finished loading 1 libraries.
,W/VideoCapabilities( 7161): Unsupported mime video/mp4v-esdp
V/DownloadManager( 3294): DownloadService onDestroy
,D/Finsky  ( 7178): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 7201): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7201): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/Finsky  ( 7178): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/VideoCapabilities( 7161): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7161): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7161): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7161): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7161): Unrecognized profile 2130706433 for video/avc
D/NativeLibraryUtils( 7201): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  955): Process com.google.android.apps.magazines (pid 6875) has died
I/vclib   ( 7161): onServiceConnected
,W/Babel   ( 7161): Attempted to change video mute state without an active call.
I/NotificationManager( 7161): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  272): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 7161): propertyValue:false
,I/ActivityManager(  955): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7264 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 7161): connection state changed from UNKNOWN to CONNECTED
,D/Finsky  ( 7178): [885] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7178): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  955): Killing 6944:com.android.chrome/u0a48 (adj 15): empty #11
D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): CdmEngine::OpenSession
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
W/libprocessgroup(  955): failed to open /acct/uid_10048/pid_6944/cgroup.procs: No such file or directory
,W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=382664901
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7264): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7264): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7264): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7264): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7264): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7264):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7264):   adb logcat -s GAv4
D/sensors_hal_Time(  955): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  955): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  955): tsOffsetIs: Apps: 114854596420; DSPS: 3862011; Offset : -3015083283
,W/GAv4    ( 7264): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7264): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7264): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 7201): CheckpointMarkThreadRoots callback created = 0xb042d5d0
,I/art     ( 7201): CheckpointMarkThreadRoots callback created = 0xb042d5c0
,I/WebViewFactory( 7264): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7264): Time to load native libraries: 2 ms (timestamps 5259-5261)
,I/LibraryLoader( 7264): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7264): Binding Chromium to main looper Looper (main, tid 1) {91b1dee}
I/LibraryLoader( 7264): Expected native library version number "",actual native library version number ""
I/chromium( 7264): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7264): Initializing chromium process, singleProcess=true
W/art     ( 7264): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7264): ApplicationContext is null in ApplicationStatus
W/chromium( 7264): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7264): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7264): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7264): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7264): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7264): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7264): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7264): Remote Branch: 
I/Adreno-EGL( 7264): Local Patches: 
I/Adreno-EGL( 7264): Reconstruct Branch: 
,V/AudioPolicyService(  279): registerClient() client 0xb4027840, uid 10079
,W/AudioManagerAndroid( 7264): Requires BLUETOOTH permission
I/NSApplication( 7264): Starting up...
I/ActivityManager(  955): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7323 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  955): Killing 6972:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 22.245ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.539ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.962ms
,W/libprocessgroup(  955): failed to open /acct/uid_10086/pid_6972/cgroup.procs: No such file or directory
,I/dex2oat ( 7333): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7333): dex2oat took 109.217ms (threads: 4)
,I/Adreno-EGL( 7201): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7201): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7201): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7201): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7201): Remote Branch: 
I/Adreno-EGL( 7201): Local Patches: 
I/Adreno-EGL( 7201): Reconstruct Branch: 
,I/Adreno-EGL( 7201): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7201): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7201): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7201): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7201): Remote Branch: 
I/Adreno-EGL( 7201): Local Patches: 
I/Adreno-EGL( 7201): Reconstruct Branch: 
,I/ActivityManager(  955): Process com.google.android.music:main (pid 7003) has died
,I/WVCdm   (  279): CdmEngine::OpenSession
,I/ActivityManager(  955): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7352 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7352): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  955): Killing 7039:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  955): failed to open /acct/uid_10021/pid_7039/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  955): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7379 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/WVCdm   (  279): CdmEngine::CloseSession
W/ResourcesManager( 7379): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=205168418
D/BluetoothManagerService(  955): Message: 20
D/BluetoothManagerService(  955): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3873a07:true
,D/BluetoothAdapterService(512353864)( 1972): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31523de
D/BluetoothAdapterService(512353864)( 1972): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31523de
I/ActivityManager(  955): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7401 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7379): Create singleton instance
,D/UEI.SmartControl( 7401): Quickset Services start...
,I/UEI.SmartControl( 7401): Manufacture = LGE
D/UEI.SmartControl( 7401): File observer start...
,E/UEI.SmartControl( 7401): IR Port is disabled: false
D/UEI.SmartControl( 7401): Starting file observer...
D/UEI.SmartControl( 7401): Extracting JNI libs...
D/UEI.SmartControl( 7401): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7379): getMode name:com.lge.qremote
,I/CheckinService( 4432): Checkin interval check for package: unspecified last checkin: 1453102482665 min interval config: 0 actual interval: 36039
,D/WearableService( 1735): callingUid 10006, callindPid: 1735
,D/LocationInitializer( 4432): Restart initialization of location
E/MDM     ( 1735): [83] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,W/ContextImpl( 3735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/UEI.SmartControl( 7401): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7401): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7401): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/AudioManager( 7379): getMode name:com.lge.qremote
,I/UEI.SmartControl( 7401): --- Selecting new region: 2
,I/UEI.SmartControl( 7401): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7401): Platform has CIR...
D/UEI.SmartControl( 7401): NO CIR support, need to check package...
I/UEI.SmartControl( 7401): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7401): QS Service created
E/UEI.SmartControl( 7401): QS start get config
,D/UEI.SmartControl( 7401): Loading JNI Libs...
,D/UEI.SmartControl( 7401):  configuring local db...
D/UEI.SmartControl( 7401):  ---- Has DB8: true
,D/UEI.SmartControl( 7401): QS start statue = true Error code = 0
D/UEI.SmartControl( 7401): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7401): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7401): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7401): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7401): IrrcClient ++ 
D/irrcClient( 7401): getIrrcService ++ 
D/irrcClient( 7401): getIrrcService -- 
D/irrcClient( 7401): IrrcClient -- 
W/irrc_jni( 7401): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7401): Services init done
D/UEI.SmartControl( 7401): QS Service init finished
I/UEI.SmartControl( 7401): Device manager: loading config....
D/UEI.SmartControl( 7401): QS Service version name: 0.1.73
D/UEI.SmartControl( 7401): QS Service version code: 1073
D/UEI.SmartControl( 7401): Service requested: Control
D/UEI.SmartControl( 7401): Config is loaded...
D/UEI.SmartControl( 7401):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7401): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7401): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7401): Internal service binding...
D/UEI.SmartControl( 7401): -----IControl: 11
,D/UEI.SmartControl( 7401): Caller: com.lge.qremote
D/UEI.SmartControl( 7401): ------------ IControl registerCallback...
I/UEI.SmartControl( 7401): Registering callback...
D/UEI.SmartControl( 7401): -----IControl: 19
D/UEI.SmartControl( 7401): Caller: com.lge.qremote
I/UEI.SmartControl( 7401): Registering Services Ready callback...
I/UEI.SmartControl( 7401): Notify client services are ready...
D/UEI.SmartControl( 7401): -----IControl: 8
D/UEI.SmartControl( 7401): Caller: com.lge.qremote
I/AudioManager( 7379): getMode name:com.lge.qremote
,I/ActivityManager(  955): Killing 7138:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/ActivityManager(  955): Killing 7091:com.lge.appbox.client/u0a11 (adj 15): empty #12
,W/libprocessgroup(  955): failed to open /acct/uid_10051/pid_7138/cgroup.procs: No such file or directory
,W/libprocessgroup(  955): failed to open /acct/uid_10011/pid_7091/cgroup.procs: No such file or directory
I/AudioManager( 7379): getMode name:com.lge.qremote
,I/art     (  955): Explicit concurrent mark sweep GC freed 23075(1031KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 10.577ms total 177.185ms
I/AudioManager( 7379): getMode name:com.lge.qremote
,I/MusicWidget( 2640): mDelayedStopHandler : unbind
,I/MusicBrowser( 2682): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2682): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2682): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2682): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2682): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2682): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
I/MusicBrowser( 2682): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2682): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  955):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@146892dbcom.lge.music.MediaPlaybackService$6@3da77178
D/MusicBrowser( 2682): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2682): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2682): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2682): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2682): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@28912ce1
I/MusicBrowser( 2682): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2682): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2682): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2682): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2682): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
,I/MusicBrowser( 2682): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2682): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2682): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2682): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2682): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2682): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2682): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2682): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2682): reset
V/MediaPlayer[Native]( 2682): setListener
V/MediaPlayer[Native]( 2682): disconnect
V/MediaPlayer[Native]( 2682): destructor
,V/AudioFlinger(  279): releasing 19 from 2682 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/MediaPlayer[Native]( 2682): disconnect
D/MusicBrowser( 2682): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2682): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2682): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2682): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2682): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2682): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2682): [SmartShareManagerClient] unregisterListener: 1068372049
W/SmartShareClient( 2682): [SmartShareManagerClient] unregisterListener invalid listener: 1068372049
I/SmartShareClient( 2682): [SmartShareManagerClient] terminate service: 2682/MediaPlaybackService/740679375
E/HomeCloudIF( 2682): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2682): [SmartShareManagerClient] unbindService context:android.app.Application@15bbd0b6
V/CloudHub( 2682): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2682): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2682): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2682): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2682): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  955): Killing 7067:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/CloudHub( 2682): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29985
,W/libprocessgroup(  955): failed to open /acct/uid_1000/pid_7067/cgroup.procs: No such file or directory
,I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): L3 Terminate.
I/Adreno-EGL( 7201): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7201): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7201): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7201): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7201): Remote Branch: 
I/Adreno-EGL( 7201): Local Patches: 
I/Adreno-EGL( 7201): Reconstruct Branch: 
,I/CheckinRequestBuilder( 4432): Classify the device as Phone.
,D/libc-netbsd( 4432): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4432): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4432): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4432): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 4432): propertyValue:false
,D/libc-netbsd( 4432): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4432): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4432): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4432): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4432): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4432): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4432): Sending checkin request (9680 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinRequestBuilder( 4432): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4432): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 6332): Explicit concurrent mark sweep GC freed 2153(94KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.054ms total 51.317ms
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4432): Classify the device as Phone.
,I/CheckinTask( 4432): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4432): Checking schedule, now: 1453102521626 next: 1453629770621
,I/CheckinService( 4432): active receiver: disabled
,I/CheckinService( 4432): Checking schedule, now: 1453102521678 next: 1453629770621
,I/CheckinService( 4432): active receiver: disabled
,D/CheckinService( 4432): Recording last checkin time for package unspecified as 1453102521690
,V/SetupWizard( 7110): Connected to Gservices successfully
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  955): Killing 7264:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/ActivityManager(  955): Killing 7178:com.android.vending/u0a36 (adj 15): empty #12
,W/libprocessgroup(  955): failed to open /acct/uid_10079/pid_7264/cgroup.procs: No such file or directory
,W/libprocessgroup(  955): failed to open /acct/uid_10036/pid_7178/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7401): Internal timer expired: 1
,I/[SystemUI]QPairHandler( 1379): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1835): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  955): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1379): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1379): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1379): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1379): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/NotificationManager( 7161): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7161): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7161): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  955): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7490 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/administrator(  955): Handling package changes for user 0
,V/JNIHelp ( 7161): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 7490): onCreate
,W/AppUp4:DB( 7490):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7490):  setFingerPrint start
,I/AppUp4:DB( 7490):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,W/System  ( 7161): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7161): Installed default security provider GmsCore_OpenSSL
I/AppUp4:DB( 7490):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7490):  SDK version = 0
,I/AppUp4:DB( 7490):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7490): AppBoxApplication onCreate()
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/AppUp4:CustModeStarterReceiver( 7490): onReceive
I/AppUp4:CustModeStarterReceiver( 7490): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7490): Context : android.app.ReceiverRestrictedContext@2087932e
D/AppUp4:CustFacade( 7490): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7490): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7490): begin check event
I/AppUp4:CustModeStarterReceiver( 7490): Event For Nothing, skip.
I/ActivityManager(  955): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7513 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationService(  955): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  955): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  955): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  955): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager(  955): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  955): Process com.google.android.apps.plus (pid 7352) has died
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
V/BackupManagerService(  955): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  955): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@33b28c4a
,W/ResourcesManager( 7513): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7513): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7513): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType(  955): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/AppConfig( 7513): Total System Memory = 906309632
,I/GalleryUtils( 7513): Application Heap = 96 MB
,I/AppConfig( 7513): App Tier : NOT_DEF
D/SystemHelper( 7513): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  955): Process com.android.chrome (pid 7323) has died
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/ActivityManager(  955): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7533 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  955): applying state to connected service
W/ResourcesManager( 7533): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7533): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7533): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7533): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7533): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7533): BUILD Country: EU
I/SystemConfig( 7533): BUILD Operator: OPEN
,I/ActivityManager(  955): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7556 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7533): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7533): existFile = false
I/SystemConfig( 7533): canReadFile = false
I/SystemConfig( 7533): systemFeature RCS result false
D/SystemConfig( 7533): refreshRcsSupport() :false
,I/LockScreenSettings( 7556): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7556): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7556): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7556): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7556): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7556): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  955): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7576 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  955): Killing 2682:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  279): 2682 died, releasing its sessions
V/AudioFlinger(  279):  pid 1753 @ 0
V/AudioFlinger(  279):  pid 3240 @ 1
V/AudioFlinger(  279):  pid 3240 @ 2
,W/libprocessgroup(  955): failed to open /acct/uid_10028/pid_2682/cgroup.procs: No such file or directory
,W/ResourcesManager( 7576): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/UpdateIcingCorporaServi( 1942): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  955): Killing 7110:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1942): UpdateCorporaTask done [took 93 ms] updated apps [took 93 ms] 
,I/ActivityManager(  955): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7602 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  955): failed to open /acct/uid_10038/pid_7110/cgroup.procs: No such file or directory
,D/Finsky  ( 7602): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7602): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7602): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7602): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7602): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3294): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3294): created cursor android.database.sqlite.SQLiteCursor@1e611925 on behalf of 7602
D/Finsky  ( 7602): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7602): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7602): Skipping gmscore version check
I/ActivityManager(  955): Killing 7201:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  955): failed to open /acct/uid_10006/pid_7201/cgroup.procs: No such file or directory
,D/Finsky  ( 7602): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4432): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4432): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7602): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4432): updateResources: need to parse f{com.google.android.gms}
,I/art     ( 1735): Explicit concurrent mark sweep GC freed 27268(1948KB) AllocSpace objects, 31(496KB) LOS objects, 40% free, 13MB/22MB, paused 1.175ms total 89.821ms
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in,
I/Icing   ( 4432): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4432): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  488): init target 500000
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  955): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
D/charger_monitor(  488): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  955): Killing 7401:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7379): android.os.DeadObjectException
,W/System.err( 7379): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7379): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7379): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7379): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7379): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7379): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7379): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7379): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7379): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7379): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7379): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7379): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7379): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7379): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7379): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7379): android.os.DeadObjectException
W/System.err( 7379): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7379): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7379): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7379): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7379): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7379): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7379): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7379): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7379): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7379): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7379): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7379): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7379): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7379): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7379): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  955): failed to open /acct/uid_10089/pid_7401/cgroup.procs: No such file or directory
W/ActivityManager(  955): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  955): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7668 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7668): Quickset Services start...
,I/UEI.SmartControl( 7668): Manufacture = LGE
D/UEI.SmartControl( 7668): File observer start...
E/UEI.SmartControl( 7668): IR Port is disabled: false
D/UEI.SmartControl( 7668): Starting file observer...
D/UEI.SmartControl( 7668): Extracting JNI libs...
D/UEI.SmartControl( 7668): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7668): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7668): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7668): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7668): --- Selecting new region: 2
,I/UEI.SmartControl( 7668): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7668): Platform has CIR...
D/UEI.SmartControl( 7668): NO CIR support, need to check package...
I/UEI.SmartControl( 7668): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7668): QS Service created
E/UEI.SmartControl( 7668): QS start get config
,D/UEI.SmartControl( 7668): Loading JNI Libs...
,D/UEI.SmartControl( 7668):  configuring local db...
D/UEI.SmartControl( 7668):  ---- Has DB8: true
,D/UEI.SmartControl( 7668): QS start statue = true Error code = 0
D/UEI.SmartControl( 7668): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7668): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7668): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7668): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7668): IrrcClient ++ 
D/irrcClient( 7668): getIrrcService ++ 
,D/irrcClient( 7668): getIrrcService -- 
,D/irrcClient( 7668): IrrcClient -- 
W/irrc_jni( 7668): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7668): Services init done
I/UEI.SmartControl( 7668): Device manager: loading config....
D/UEI.SmartControl( 7668): QS Service init finished
,D/UEI.SmartControl( 7668): QS Service version name: 0.1.73
D/UEI.SmartControl( 7668): Config is loaded...
D/UEI.SmartControl( 7668): QS Service version code: 1073
D/UEI.SmartControl( 7668): Service requested: Control
I/ActivityManager(  955): Killing 7379:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7668): -----IControl: 11
D/UEI.SmartControl( 7668): Caller: com.lge.qremote
D/UEI.SmartControl( 7668): ------------ IControl registerCallback...
I/UEI.SmartControl( 7668): Registering callback...
D/UEI.SmartControl( 7668):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7668): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7668): Internal service binding...
W/libprocessgroup(  955): failed to open /acct/uid_10106/pid_7379/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/UEI.SmartControl( 7668): Internal timer expired: 1
,D/UEI.SmartControl( 7668): Service.onUnbind: IControl
D/UEI.SmartControl( 7668): Service.onDestroy
D/UEI.SmartControl( 7668): Shutdown IRRCPlayer... 
,W/irrc_jni( 7668): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7668): ~IrrcClient ++ 
D/irrcClient( 7668): ~IrrcClient -- 
W/irrc_jni( 7668): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7668): Blaster closed
D/UEI.SmartControl( 7668): Blaster closed
D/UEI.SmartControl( 7668): Shut down QS...
,D/UEI.SmartControl( 7668): Stopped file observer...
I/UEI.SmartControl( 7668): QS lib stop result = true
D/UEI.SmartControl( 7668): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  955): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  955): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  955): tsOffsetIs: Apps: 134855236933; DSPS: 4517393; Offset : -3015113973
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  955): ELAPSED_WAKEUP set : Alarm{d6bfb2 type 2 when 141778 com.google.android.gms} when 141778
,I/art     (  955): Explicit concurrent mark sweep GC freed 35630(1746KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.459ms total 165.160ms
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1735): Vacuum at: now=1453102543765 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/PowerManagerService(  955): ALS enabled for SRE
D/PowerManagerServiceEx(  955): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28355 ms ago)
,D/qdlights(  955): set_light_backlight: 253
,D/qdlights(  955): set_light_backlight: 249
D/qdlights(  955): set_light_backlight: 246
,D/qdlights(  955): set_light_backlight: 243
,D/qdlights(  955): set_light_backlight: 239
,D/qdlights(  955): set_light_backlight: 236
,D/qdlights(  955): set_light_backlight: 233
,D/qdlights(  955): set_light_backlight: 229
,D/qdlights(  955): set_light_backlight: 226
,D/qdlights(  955): set_light_backlight: 223
,D/qdlights(  955): set_light_backlight: 219
,D/qdlights(  955): set_light_backlight: 216
,D/qdlights(  955): set_light_backlight: 213
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/qdlights(  955): set_light_backlight: 209
D/qdlights(  955): set_light_backlight: 206
,D/qdlights(  955): set_light_backlight: 203
,D/qdlights(  955): set_light_backlight: 199
,D/qdlights(  955): set_light_backlight: 196
,D/qdlights(  955): set_light_backlight: 193
,D/qdlights(  955): set_light_backlight: 189
,D/qdlights(  955): set_light_backlight: 186
,D/qdlights(  955): set_light_backlight: 183
,D/qdlights(  955): set_light_backlight: 179
,D/qdlights(  955): set_light_backlight: 176
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,D/qdlights(  955): set_light_backlight: 173
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  955): set_light_backlight: 169
,D/qdlights(  955): set_light_backlight: 166
,D/qdlights(  955): set_light_backlight: 163
,D/qdlights(  955): set_light_backlight: 159
,D/qdlights(  955): set_light_backlight: 156
,D/qdlights(  955): set_light_backlight: 153
,D/qdlights(  955): set_light_backlight: 149
,D/qdlights(  955): set_light_backlight: 146
,D/qdlights(  955): set_light_backlight: 143
,D/qdlights(  955): set_light_backlight: 139
,D/qdlights(  955): set_light_backlight: 136
,D/qdlights(  955): set_light_backlight: 133
,D/qdlights(  955): set_light_backlight: 129
,D/qdlights(  955): set_light_backlight: 126
,D/qdlights(  955): set_light_backlight: 123
,D/qdlights(  955): set_light_backlight: 119
,D/qdlights(  955): set_light_backlight: 116
,D/qdlights(  955): set_light_backlight: 113
,D/qdlights(  955): set_light_backlight: 109
,D/qdlights(  955): set_light_backlight: 106
,D/qdlights(  955): set_light_backlight: 103
,D/qdlights(  955): set_light_backlight: 99
,D/qdlights(  955): set_light_backlight: 96
,D/qdlights(  955): set_light_backlight: 93
,D/qdlights(  955): set_light_backlight: 89
,D/qdlights(  955): set_light_backlight: 86
,D/qdlights(  955): set_light_backlight: 83
,D/qdlights(  955): set_light_backlight: 79
,D/qdlights(  955): set_light_backlight: 76
,D/qdlights(  955): set_light_backlight: 73
,D/qdlights(  955): set_light_backlight: 69
,D/qdlights(  955): set_light_backlight: 66
,D/qdlights(  955): set_light_backlight: 63
,D/qdlights(  955): set_light_backlight: 59
,D/qdlights(  955): set_light_backlight: 56
,D/qdlights(  955): set_light_backlight: 53
,D/qdlights(  955): set_light_backlight: 49
,D/qdlights(  955): set_light_backlight: 46
,D/qdlights(  955): set_light_backlight: 43
,D/qdlights(  955): set_light_backlight: 39
,D/qdlights(  955): set_light_backlight: 36
,D/qdlights(  955): set_light_backlight: 33
,D/qdlights(  955): set_light_backlight: 29
,D/qdlights(  955): set_light_backlight: 26
,D/qdlights(  955): set_light_backlight: 23
,D/qdlights(  955): set_light_backlight: 19
,D/qdlights(  955): set_light_backlight: 16
,D/qdlights(  955): set_light_backlight: 13
,D/qdlights(  955): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  955): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  955): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  955): tsOffsetIs: Apps: 154855905468; DSPS: 5172775; Offset : -3015116982
,I/PowerManagerService(  955): ALS enabled for SRE
D/PowerManagerServiceEx(  955): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35349 ms ago)
I/PowerManagerService(  955): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  955): ALS enabled for SRE
D/PowerManagerServiceEx(  955): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35359 ms ago)
W/ContextImpl(  955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  955): Sleeping (uid 1000)...
D/LPWGController(  955): [updateScreenState] screen on = false
D/LPWGController(  955): disable proximity sensor
D/LPWGController(  955): enable proximity sensor
,I/SensorManager(  955): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3151d77b] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  955): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  955): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  955): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  955): activate: handle is 48, enable
V/sensors_hal_Ctx(  955): activate sensors is 1400000000000
D/sensors_hal_Thresh(  955): enable: handle=48
I/sensors_hal_SAM(  955): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  955): waitForResponse: timeout=1000
V/sensors_hal_SAM(  955): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  955): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  955): enable: Received response: 0
D/PowerManagerServiceEx(  955): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35400 ms ago)
I/Adreno-EGL(  955): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  955): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  955): Build Date: 03/02/15 Mon
I/Adreno-EGL(  955): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  955): Remote Branch: 
I/Adreno-EGL(  955): Local Patches: 
I/Adreno-EGL(  955): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (910 us)
,I/Sensors (  435): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  955): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  955): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  955): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  955): processInd: handle 48, count=1
V/sensors_hal_Thresh(  955): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  955): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  955): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  955): poll: count: 256
I/sensors_hal_Ctx(  955): poll: released wakelock sensor_ind
D/sensors_hal_Util(  955): waitForResponse: timeout=0
D/LPWGController(  955): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  955): current mode = 1  value = 1 1
I/LPWGController(  955): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  955): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/qdlights(  955): set_light_backlight: 0
,I/SensorManager(  955): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  955): activate: handle is 46, disable
V/sensors_hal_Ctx(  955): activate sensors is 1000000000000
D/sensors_hal_LP2(  955): enable: handle=46
D/sensors_hal_LP2(  955): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  955): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  955): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/sensors_hal_SAM(  955): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  955): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  955): Display changed displayId=0
,D/DSDPConnection( 1753): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
D/SurfaceControl(  955): Excessive delay in setPowerMode(): 170ms
,I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  955): Got set_interactive hint
D/KeyguardViewMediator( 1379): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1334): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1379): notifyScreenOffLocked
D/KeyguardViewMediator( 1379): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1379): handleNotifyScreenOff
,D/SmartCoverViewMediator( 1334): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1334): handleNotifyScreenOFF
D/ScreenTurnOffBySensor( 1379): unregisterProximitySensor
,D/WifiServerServiceExt(  955): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1379): onScreenTurnedOff why = 3
V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 955
D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=on
,V/voice   (  279): voice_set_parameters: enter: screen_state=on
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: exit
V/voice   (  279): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  279): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  279): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  279): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  279): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  279): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  279): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  279): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/WifiServerServiceExt(  955): set CMD_KT_SCAN_INTERVAL
,D/GpsLocationProvider(  955): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1835): |CORE| sendScreenState: state:true
I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1805): lockStatus = 0
D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): updateLightsLocked : turn off led
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1805): RESTART MSG
,D/SplitWindow(  955): check instance of lgWin Window{172ed5d6 u0 SearchPanel}
,D/LNfcService( 1788): action : android.intent.action.SCREEN_ON
,D/NfcServiceNXP( 1788): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1788): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
,D/LNfcService( 1788): isRequireNfcCRouting() return true
D/LNfcService( 1788): isHCERoutingtoHost() return : true
D/NfcService( 1788): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): newParams.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): screenState= 3
D/NfcService( 1788): Discovery configuration equal, not updating.
D/InputDispatcher(  955): Window went away: Window{3584db66 u0 SearchPanel}
,I/[SystemUI]Clock( 1379): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1379): time changed, timezoneChanged : false
,D/Ulp_jni (  955): JNI:system_update. Event-0
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
I/Sensors (  435): sns_pwr.c(301):releasing wakelock
,D/WeatherService( 2661): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 8:35:58
,D/WeatherService( 2661): 2 : ACTION screen on
D/WeatherService( 2661): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2661): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2661): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 8:35:58
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): ACTION_SCREEN_ON
D/AppCleanupService( 4236): android.intent.action.SCREEN_ON
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 955
D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=off
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
D/GpsLocationProvider(  955): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/WifiController(  955): CMD_SCREEN_OFF 
D/WifiController(  955): shouldWifiStayAwake TRUE
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1835): |CORE| sendScreenState: state:false
,I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1805): clear
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): updateLightsLocked : turn on led
E/LEDService( 1805): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1805): Can't handle this request of patternId:0
D/LEDHandler( 1805): RESTART MSG
D/LNfcService( 1788): action : android.intent.action.SCREEN_OFF
,I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
D/NfcServiceNXP( 1788): mScreenState : 1, mInProvisionMode : false
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
D/WeatherService( 2661): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 8:35:58
D/WeatherService( 2661): 2 : ACTION screen off
,D/WeatherService( 2661): 2 : TimeTick Receiver Unregister
D/WeatherService( 2661): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 8:35:58
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): ACTION_SCREEN_OFF
D/AppCleanupService( 4236): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4236): AppUsageStatsSaveTask
,E/NxpNfcJni( 1788): getReconnectState = 0x0
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
D/LNfcService( 1788): isRequireNfcCRouting() return true
D/LNfcService( 1788): isHCERoutingtoHost() return : true
,D/NfcService( 1788): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): newParams.techmask= mTechMask: 0
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): screenState= 1
E/NxpNfcJni( 1788): getReconnectState = 0x0
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  955): acquireWakeLockInternal: lock=335319980, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=955
,D/KeyguardViewMediator( 1379): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
V/AlarmManager(  955): ELAPSED_WAKEUP set : Alarm{1d9c7057 type 2 when 161226 com.android.systemui} when 161226
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1753): getCallState : 0
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1379): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1379): doKeyguard: not showing because lockscreen is off
D/PowerManagerServiceEx(  955): releaseWakeLockInternal: lock=335319980 [*alarm*], flags=0x0
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
D/charger_monitor(  488): init target 500000
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  955): battery changed pluggedType: 2
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  955): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  955): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  955): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  955): tsOffsetIs: Apps: 174856610564; DSPS: 5828158; Offset : -3015113451
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  488): init target 500000
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  955): battery changed pluggedType: 2
V/AlarmManager(  955): ELAPSED_WAKEUP set : Alarm{208744 type 2 when 187301 com.google.android.gms} when 187301
,I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
,I/PhenotypeConfigurator( 1735): Scheduling Phenotype for one-off execution 10297 seconds from now (1453102589202)
,D/GetConfigurationSnapshotOperation( 1735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1735): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  955): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 1735): propertyValue:false
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ClearcutLoggerApiImpl( 1735): disconnect managed GoogleApiClient
,D/LocationManagerService(  955): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/LocationManagerService(  955): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  955): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  955): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  955): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  955): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/AlarmManager(  955): ELAPSED_WAKEUP set : Alarm{38d64974 type 2 when 191722 android} when 191722
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  955): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  955): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  955): tsOffsetIs: Apps: 194857413526; DSPS: 6483544; Offset : -3015104416
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  955): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  955): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  955): tsOffsetIs: Apps: 214858178049; DSPS: 7138929; Offset : -3015102598
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  955): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  955): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  955): tsOffsetIs: Apps: 234865339291; DSPS: 7794523; Offset : -3015082391
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  488): init target 500000
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  955): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  955): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  955): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  955): tsOffsetIs: Apps: 254866134440; DSPS: 8449910; Offset : -3015111295
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  955): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  955): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  955): tsOffsetIs: Apps: 274866908703; DSPS: 9105295; Offset : -3015100179
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  955): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  955): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  955): tsOffsetIs: Apps: 294867711664; DSPS: 9760681; Offset : -3015090675
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  488): init target 500000
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  955): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  955): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  955): tsOffsetIs: Apps: 314868590823; DSPS: 10416070; Offset : -3015096578
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  955): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  955): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  955): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  955): tsOffsetIs: Apps: 334869451232; DSPS: 11071458; Offset : -3015090635
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  955): remove 1f021870
D/LocationManagerService(  955): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  955): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  955): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  955): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  955): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6349): --= Surplus to requirements =--
I/jxcore-log( 6349): 
I/jxcore-log( 6349): ****TEST TOOK:  ms ****
I/jxcore-log( 6349): 
I/jxcore-log( 6349): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6349): 
,D/AndroidRuntime( 7824): 
D/AndroidRuntime( 7824): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7824): CheckJNI is OFF
,D/AndroidRuntime( 7824): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  955): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  955): Killing 6349:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,I/WindowState(  955): WIN DEATH: Window{2bd3e025 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  955): Focus left window: Window{2bd3e025 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  955): Window went away: Window{2bd3e025 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  955): Skipping PackageSetting{14a5b10e com.example.hello/10317} due to missing metadata
,I/ActivityManager(  955):   Force finishing activity ActivityRecord{accab92 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  955): Display changed displayId=0
D/DSDPConnection( 1753): Display #0 changed.
,W/ActivityManager(  955): Spurious death for ProcessRecord{156ce9d 6349:com.test.thalitest/u0a316}, curProc for 6349: null
,I/ActivityManager(  955): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  955):   Force finishing activity ActivityRecord{accab92 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  955): Duplicate finish request for ActivityRecord{accab92 u0 com.test.thalitest/.MainActivity t222 f}
,I/art     ( 1942): Explicit concurrent mark sweep GC freed 9380(547KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 1.712ms total 75.709ms
,D/KeyguardModel( 1379): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1735): Ignoring removeGeofence because network location is disabled.
,I/art     ( 4432): Explicit concurrent mark sweep GC freed 4083(213KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 14MB/18MB, paused 1.064ms total 93.974ms
I/QCNEJ   ( 1835): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  955): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 3735): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3735): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3735): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3735): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3735): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3735): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3735): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3735): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3735): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3735): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3735): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3735): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/ActivityManager(  955): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7854 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 27.534ms
,I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
I/[SystemUI]QSlideListController( 1379): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
D/KeyguardModel( 1379): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1379): createShortcutInfo...
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 323us total 24.796ms
D/KeyguardModel( 1379): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1379): createShortcutInfo...
,I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 348us total 24.670ms
,I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
I/Activity( 1878): Activity.onPostResume() called 
,W/ResourceType( 1379): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1379): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1379): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1379): createShortcutInfo...
W/ResourceType( 1379): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1379): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/art     (  955): Explicit concurrent mark sweep GC freed 43099(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 11.705ms total 213.413ms
D/KeyguardModel( 1379): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1379): createShortcutInfo...
I/art     (  955): WaitForGcToComplete blocked for 73.187ms for cause Explicit
,I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1379): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1379): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1379): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1379): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1379): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1379): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1379): handleShortcutListChanged...
,D/KeyguardModel( 1379): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1379): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/SystemUI[Framework](  955): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ResourcesManager( 7854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7854): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/PhoneWindowManagerEx(  955): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  955): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  955): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  955): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@d1210f6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  955): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  955): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  955): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  955): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  955): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  955): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@d1210f6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  955): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 7854): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/InputDispatcher(  955): Focus entered window: Window{c2699d3 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1379): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1379): createShortcutInfo...
,W/ResourceType( 1379): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1379): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1379): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1379): createShortcutInfo...
W/ResourceType( 1379): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1379): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1379): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1379): createShortcutInfo...
W/ResourceType( 1379): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1379): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/administrator(  955): Handling package changes for user 0
,D/KeyguardModel( 1379): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1379): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1379): handleShortcutListChanged...
,I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  955): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  955): Got RemoteException sending setActive(false) notification to pid 6349 uid 10316
I/art     (  955): Explicit concurrent mark sweep GC freed 5342(293KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.678ms total 294.731ms
,I/LGEmail ( 7854): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,D/LGEmail ( 7854): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,I/Timeline(  955): Timeline: Activity_windows_visible id: ActivityRecord{1850c0b2 u0 com.lge.launcher2/.Launcher t221} time:352944
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1598): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1878): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/AndroidRuntime( 7824): Shutting down VM
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
I/NotificationService(  955): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  955): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/JobSchedulerService(  955): Receieved: android.intent.action.PACKAGE_REMOVED
,D/PhoneStatusBar( 1379): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
,D/TaskPersister(  955): removeObsoleteFile: deleting file=222_task.xml
D/PhoneStatusBar( 1379): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1379): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1379):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1379): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/PackageChangeReceiver( 7854): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,W/ResourcesManager(  955): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AppUp4:PreloadHelper( 7490): added Exclude : com.test.thalitest
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  955): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7884 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  955): Killing 7161:com.google.android.talk/u0a61 (adj 15): empty #11
W/ResourceType(  955): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  955): failed to open /acct/uid_10061/pid_7161/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume

```
