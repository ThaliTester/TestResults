#### Test 506502781c2754f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/qtaguid ( 5716): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5716): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5716): untagSocket(41) failed with errno -22
--------- beginning of system
W/ActivityThread( 6361): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6361): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34409481: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6361): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6361): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6361): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 6361): Reading stored module config
D/WearableService( 1729): callingUid 10006, callindPid: 1729
E/MDM     ( 1729): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4265): Restart initialization of location
D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/ChimeraCfgMgr( 6361): Loading module com.google.android.gms.car from APK com.google.android.gms
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1729): No location to return for getLastLocation()
W/FusedLocationProvider( 1729): location=null
D/CAR.SERVICE( 6361): Connecting to CarCallService...
D/NativeLibraryUtils( 6361): Install completed successfully. count=14 extracted=0
I/art     ( 5716): CheckpointMarkThreadRoots callback created = 0xb042d500
I/art     ( 6361): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6361): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5716): CheckpointMarkThreadRoots callback created = 0xb042d8e0
D/CAR.SERVICE( 6361): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 6361): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6361): Creating a new PhoneAdapter instance
W/ActivityManager(  853): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6361): setListener: com.google.android.gms.car.dn@10653944
W/ActivityManager(  853): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6361): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6361): Starting CarCallService with initial phone null
I/NotificationManager( 6361): com.google.android.gms: cancel(10436) by com.google.android.gms
D/CAR.SERVICE( 6361): Package validated; name: com.android.vending
I/NotificationManager( 5716): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5716): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/AndroidRuntime( 6409): 
D/AndroidRuntime( 6409): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6409): CheckJNI is OFF
I/ActivityManager(  853): Process com.android.contacts (pid 6216) has died
D/AlertService( 6135): Beginning updateAlertNotification
D/AndroidRuntime( 6409): Calling main entry com.android.commands.am.Am
D/AlertService( 6135): No fired or scheduled alerts
I/NotificationManager( 6135): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6135): com.android.calendar: cancel(19) by com.android.calendar
I/ActivityManager(  853): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/NotificationManager( 6135): com.android.calendar: cancel(20) by com.android.calendar
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{3e49e141 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{3e49e141 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  853): AppWindowTokenEx init.. 
D/ContextHelper(  853): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  853): Focus left window: Window{250e8d18 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6409): Shutting down VM
D/AlertService( 6135): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
I/NotificationManager(  853): android: cancelAsUser(2) by android
D/AlarmScheduler( 6135): No events found starting within 1 week.
D/SplitWindow(  853): check instance of lgWin Window{2935e11f u0 Starting com.test.thalitest}
I/ActivityManager(  853): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6435 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  853): Starting window displayed
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17b2465c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1371): draw background and invalidate : color = e000000
D/BarTransitions( 1371): draw background and invalidate : color = f0e0e0e
I/HotwordDetector( 1937): Closing mic
I/MicrophoneInputStream( 1937): mic_close com.google.android.apps.gsa.speech.audio.u@1ac5a22
V/AudioRecord( 1937): stop()
D/AudioRecord( 1937): AudioRecord->stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
,V/AudioFlinger(  283): Record stopped OK
V/AudioPolicyManager(  283): stopInput() input 16
V/AudioPolicyService(  283): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  283): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  283): ThreadBase::setParameters() routing=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3831000
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
I/qtaguid ( 5716): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5716): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5716): untagSocket(41) failed with errno -22
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
V/AudioPolicyManager(  283): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  283): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  283): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyService(  283): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  283): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  283): setParameters(): io 16, keyvalue hotword_active=0, calling pid 283
V/AudioFlinger(  283): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3831000
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioFlinger(  283): releasing 15 from 1937 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioPolicyManager(  283): releaseInput() 16
V/AudioFlinger(  283): purging stale effects
V/AudioPolicyManager(  283): closeInput(16)
V/AudioFlinger(  283): closeInput() 16
V/AudioSystem(  283): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  283): ThreadBase::exit
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioSystem( 3209): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  283): RecordThread 0xb3831000 exiting
V/AudioSystem( 1937): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  853): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1371): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1747): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2804): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1963): ioConfigChanged() event 4, ioHandle 16
D/audio_hw_primary(  283): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  283): releaseInput() exit
V/AudioFlinger(  283): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  283): removeClient_l() pid 1937, calling pid 283
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1937): Stopping hotword detection.
D/ContextHelper( 6435): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/HotwordRecognitionRnr( 1937): Hotword detection finished
I/WebViewFactory( 6435): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6435): Time to load native libraries: 11 ms (timestamps 6719-6730)
I/LibraryLoader( 6435): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6435): Binding Chromium to main looper Looper (main, tid 1) {1deb0e97}
I/LibraryLoader( 6435): Expected native library version number "",actual native library version number ""
I/chromium( 6435): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ResourcesManager( 5716): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5716): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/BrowserStartupController( 6435): Initializing chromium process, singleProcess=true
W/art     ( 6435): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6435): ApplicationContext is null in ApplicationStatus
W/ResourcesManager( 5716): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Finsky  ( 5716): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{267ed570 type 0 when 1450657956615 com.android.vending} when 1450657956615
W/chromium( 6435): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6435): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6435): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6435): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6435): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6435): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6435): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6435): Remote Branch: 
I/Adreno-EGL( 6435): Local Patches: 
I/Adreno-EGL( 6435): Reconstruct Branch: 
D/DeviceConnectionService( 1729): client connected with version: 8296000
D/Finsky  ( 5716): [694] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5716): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5716): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  853): android: cancelAsUser(2) by android
D/libc-netbsd( 5716): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5716): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5716): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5716): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
V/AudioPolicyService(  283): registerClient() client 0xb4027840, uid 10316
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5716): propertyValue:false
D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a6a7aa0:true
,D/BluetoothAdapterService(684195123)( 1963): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@316db1a1
W/art     ( 6435): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6435): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6435): CordovaWebView is running on device made by: LGE
,W/art     ( 6435): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6435): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 6435): Activity.onPostResume() called 
,D/OpenGLRenderer( 6435): Render dirty regions requested: true
I/OpenGLRenderer( 6435): Initialized EGL, version 1.4
D/OpenGLRenderer( 6435): Enabling debug mode 0
,D/Atlas   ( 6435): Validating map...
,D/SplitWindow(  853): check instance of lgWin Window{1ce1cbd0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6435): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/ActivityManager(  853): Killing 6135:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10013/pid_6135/cgroup.procs: No such file or directory
,D/InputDispatcher(  853): Focus entered window: Window{1ce1cbd0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/ProcessCpuTracker(  853): Skipping unknown process pid 6454
W/ProcessCpuTracker(  853): Skipping unknown process pid 6455
,W/ProcessCpuTracker(  853): Skipping unknown process pid 6457
W/ProcessCpuTracker(  853): Skipping unknown process pid 6462
W/ProcessCpuTracker(  853): Skipping unknown process pid 6489
W/InputMethodManagerService(  853): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  853): Displayed com.test.thalitest/.MainActivity: +1s194ms
I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{15ce6e6 u0 com.test.thalitest/.MainActivity t220} time:97442
,I/Timeline( 6435): Timeline: Activity_idle id: android.os.BinderProxy@30043252 time:97448
W/BindingManager( 6435): Cannot call determinedVisibility() - never saw a connection for the pid: 6435
,D/JsMessageQueue( 6435): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  853): Process com.google.android.talk (pid 5854) has died
,D/jxcore_app_log( 6435): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622768128
,D/JX-Cordova( 6435): jxcore cordova android initializing
I/art     ( 6435): CheckpointMarkThreadRoots callback created = 0x9f7d9c70
,I/art     ( 6435): CheckpointMarkThreadRoots callback created = 0x9f7d9c40
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/art     (  853): Explicit concurrent mark sweep GC freed 22233(1086KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.479ms total 196.841ms
,I/art     ( 6435): Background sticky concurrent mark sweep GC freed 901(80KB) AllocSpace objects, 0(0B) LOS objects, 1% free, 19MB/19MB, paused 7.507ms total 21.579ms
,W/jxcore-log( 6435): Initializing JXcore engine
,W/jxcore-log( 6435): JXcore engine is ready
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/jxcore-log( 6435): Starting JXcore engine
,W/.test.thalitest( 6435): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6738]" dev="sockfs" ino=6738 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6435): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6435): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7530]" dev="sockfs" ino=7530 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6435): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6435): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6435): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[29180]" dev="sockfs" ino=29180 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6435): Platform android
W/jxcore-log( 6435): 
,W/jxcore-log( 6435): Process ARCH arm
W/jxcore-log( 6435): 
D/CAR.SERVICE( 6361): mConnectedToCar = false, abort
,E/ActivityThread( 6361): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2f0580ac that was originally bound here
E/ActivityThread( 6361): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2f0580ac that was originally bound here
E/ActivityThread( 6361): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6361): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6361): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6361): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6361): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6361): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6361): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6361): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6361): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6361): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6361): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6361): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6361): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6361): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6361): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6361): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6361): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6361): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6361): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6361): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6361): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6361): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6361): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3a1caa57 that was originally bound here
E/ActivityThread( 6361): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3a1caa57 that was originally bound here
E/ActivityThread( 6361): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6361): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6361): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6361): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6361): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6361): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6361): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6361): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6361): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6361): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6361): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6361): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6361): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6361): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6361): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6361): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6361): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6361): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6361): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6361): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6361): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  853): Unbind failed: could not find connection for android.os.BinderProxy@195344e8
,I/jxcore-log( 6435): JXcore Cordova bridge is ready!
I/jxcore-log( 6435): 
W/jxcore-log( 6435): JXcore engine is started
I/chromium( 6435): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 6435): Skipped 191 frames!  The application may be doing too much work on its main thread.
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{3946e9a6 type 0 when 1450657961237 com.google.android.googlequicksearchbox} when 1450657961237
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  488): init target 500000
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 297, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
D/WifiController(  853): battery changed pluggedType: 2
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/charger_monitor(  488): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 298, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/jxcore-log( 6435): Toggling radios to true
I/jxcore-log( 6435): 
,D/BluetoothAdapter( 6435): enable(): BT is already enabled..!
I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
D/WifiServiceImplEx(  853): setWifiEnabled: true pid=6435, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  853): setWifiEnabled: true pid=6435, uid=10316
D/WifiServiceImplEx(  853): disconnect pid=6435, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  853): reconnect pid=6435, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6435): Radios toggled
I/jxcore-log( 6435): 
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  273): 
I/wpa_supplicant( 2706): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/jxcore-log( 6435): Got Device Bluetooth address: F8:95:C7:87:85:54
I/jxcore-log( 6435): 
,I/wpa_supplicant( 2706): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  853): WifiStateMachine: Leaving Connected state
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/jxcore-log( 6435): Perf Test app loaded loaded
I/jxcore-log( 6435): 
,D/WfdsMonitor( 1801): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/jxcore-log( 6435): check test folder
I/jxcore-log( 6435): 
,I/jxcore-log( 6435): found test : ./testFindPeers.js
I/jxcore-log( 6435): 
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  853): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 7
I/jxcore-log( 6435): found test : ./testSendData.js
I/jxcore-log( 6435): 
,V/NativeCrypto( 1729): Read error: ssl=0xaaede800: I/O error during system call, Connection timed out
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,V/NativeCrypto( 1729): SSL shutdown failed: ssl=0xaaede800: I/O error during system call, Broken pipe
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 10
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 7
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,D/WifiHS20(  853): hidePasspointNotification off =false
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:43.456 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  853): ignoring duplicate network state non-change
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  853): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,I/jxcore-log( 6435): found test : ./testSendData2.js
I/jxcore-log( 6435): 
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): ValidatedState{ when=-3ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=-13ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Forcing reevaluation
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
E/jxcore  ( 6435): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 6435): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,I/ActivityManager(  853): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6592 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
E/WifiStateMachine(  853): Start Disconnecting Watchdog 1
D/WifiHS20(  853): hidePasspointNotification off =false
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  853): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/chromium( 6435): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/wpa_supplicant( 2706): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:43.531 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/ConnectivityService(  853): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  853): disableDataServiceNotify
D/DSQN    (  853): stop dsqn bin
I/ActivityManager(  853): Process com.google.android.gm (pid 6006) has died
D/WifiHS20(  853): hidePasspointNotification off =false
,D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:43.574 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNetworkAgent(  853): NetworkAgent: NetworkAgent channel lost
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/WifiHS20(  853): hidePasspointNotification off =false
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:43.6 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DhcpStateMachine(  853): StoppedState
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DhcpStateMachine(  853): StoppedState{ when=-99ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  853): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/ConnectivityService(  853): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  853): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Disconnected - quitting
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:43.62 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateDISCONNECTED
D/CSLegacyTypeTracker(  853): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  853): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateSCANNING
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  853): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1836): |CORE| No family connected
,D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  853): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  853): MasterInitialState.processMessage what=3
D/WIFI    (  853): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  853): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/Tethering(  853): MasterInitialState.processMessage what=3
D/NetworkManagementService(  853): Removing idletimer
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1747): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1747):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,W/Settings(  853): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ResourcesManager( 6592): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6592): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6592): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6592): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6592): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager(  853): Process com.google.android.apps.plus (pid 6255) has died
,D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/IndexDatabaseHelper( 6592): Using schema version: 115
,I/IndexDatabaseHelper( 6592): Index is fine
V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
I/ActivityManager(  853): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6620 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6620): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6620): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6620): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
I/PCSuite ( 6620): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6620): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6620): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6642 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  853): Process com.android.providers.calendar (pid 6311) has died
,W/ResourcesManager( 6642): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6642): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6642): MmsConfig.loadMmsSettings
I/Babel_SMS( 6642): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6642): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6642): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6642): MmsConfig.loadFromResources
E/Babel_SMS( 6642): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6642): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6642): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6642): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6642): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 6642): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6642): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6642): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6642): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6642): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6642): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6642): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6642): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6642): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6642): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6642): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6642): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6642): found sensor: Motion Accel, handle=46
W/Settings( 6642): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6642): startup - clean
I/Babel   ( 6642): deleted: false for 0
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2706): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/ActivityManager(  853): Process com.lge.lockscreensettings (pid 6238) has died
,I/art     ( 6642): CheckpointMarkThreadRoots callback created = 0xb042d8f0
,V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
D/LocSvc_java(  853): onReceive
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2706): wlan0: Associated with c0:ff:d4:d3:aa:48
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:44.693 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateASSOCIATED
I/PCSuite ( 6620): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6620): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6620): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:44.699 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:44.718 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:44.719 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
W/AudioCapabilities( 6642): Unsupported mime audio/x-lg-flac
I/PCSuite ( 6620): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
I/wpa_supplicant( 2706): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/PCSuite ( 6620): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6620): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/wpa_supplicant( 2706): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
W/AudioCapabilities( 6642): Unsupported mime audio/adpcm
V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServiceExtension(  853): setVHTCapabilityType  : false
W/AudioCapabilities( 6642): Unsupported mime audio/g726
W/AudioCapabilities( 6642): Unsupported mime audio/x-ms-wma
I/art     ( 6642): CheckpointMarkThreadRoots callback created = 0xb042d8d0
D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6592): Not supported operator for automatic switch
W/AudioCapabilities( 6642): Unsupported mime audio/wma-voice
V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
I/WifiServerServiceExt(  853): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  853): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,I/WifiServiceExtension(  853): setSecurityType  : 2
V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
W/art     ( 6642): Suspending all threads took: 16.780ms
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:44.798 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:44.8 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
,W/VideoCapabilities( 6642): Unsupported mime video/mjpg
D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
W/VideoCapabilities( 6642): Unsupported mime video/theora
D/ConnectivityService(  853): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  853): Got NetworkAgent Messenger
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  853): NetworkAgent connected
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  277): Setting iface cfg
E/WifiStateMachine(  853): Start Dhcp Watchdog 2
D/DhcpStateMachine(  853): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  853): WaitBeforeStartState
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateGROUP_HANDSHAKE
D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
,D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
W/AudioCapabilities( 6642): Unsupported mime audio/evrc
W/AudioCapabilities( 6642): Unsupported mime audio/qcelp
W/VideoCapabilities( 6642): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6642): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6642): Unsupported mime audio/qcelp
W/AudioCapabilities( 6642): Unsupported mime audio/evrc
W/VideoCapabilities( 6642): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6642): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6642): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6642): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6642): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6642): Unrecognized profile 2130706433 for video/avc
E/WifiStateMachine(  853): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  853): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  853): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService(  853): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1894eedb target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1894eedb target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  853): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  277): Setting iface cfg
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 6
D/DhcpStateMachine(  853): DHCP Start wake lock is acquired.
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  277): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  853): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
I/vclib   ( 6642): onServiceConnected
W/Babel   ( 6642): Attempted to change video mute state without an active call.
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateCOMPLETED
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  853): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  853): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  853): ignoring duplicate network state non-change
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:44.954 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  853): Adding iface wlan0 to network 101
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:44.963 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
E/WifiStateMachine(  853): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,E/ConnectivityService(  853): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  853): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  853): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:44.985 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
I/NotificationManager( 6642): com.google.android.talk: cancel(10436) by com.google.android.talk
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  853): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 3
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  277): netlink response contains error (File exists)
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService(  853): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  853): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService(  853): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  853): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  853): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWOR,K_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Nat464Xlat(  853): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:44.997 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  853): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  853): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  853):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  853): currentScore = 0, newScore = 20
D/ConnectivityService(  853):    accepting network in place of null
D/ConnectivityService(  853): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1747): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1747):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  853): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  853): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  853): MasterInitialState.processMessage what=3
D/CSLegacyTypeTracker(  853): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  853): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  853): validation of new default Network = false
D/ConnectivityService(  853): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  853): enableDataServiceNotify 
D/DSQN    (  853): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 3
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] Start DNSResolver start to wait
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] wait 500ms before dns check
V/NetworkPolicy(  853): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService(  853): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
I/DSQN    ( 6687): DSQN samuel.seo ver 141203
E/DSQN    ( 6687): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6687): created command queue thread
I/DSQN    ( 6687): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6687): Interface wlan0 netmask 255.255.255.0 0xc0a80186
V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
,V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
I/PCSuite ( 6620): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6620): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6592): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6592): MCCMNC not supported: null
I/PCSuite ( 6620): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6620): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/DhcpStateMachine(  853): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  853): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  853): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/dhcpcd  ( 6690): version 5.5.6 starting
E/dhcpcd  ( 6690): get_duid: Read-only file system
W/SQLiteConnectionPool( 4265): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/dhcpcd  ( 6690): wlan0: rebinding lease of 192.168.1.134
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] DNSResolver start dns
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out(  853): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 6687): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6687): restart monitoring
,D/LGDataListener(  277): argv[0]=dsqncommand
D/LGDataListener(  277): argv[1]=wlan0
D/LGDataListener(  277): argv[2]=1
D/LGDataListener(  277): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  853): DSQM DsqnNotification wlan0  1
D/DSQN    (  853): start to monitor internet connection
I/DSQN    ( 6687): dsqn report finish
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Dec 2015 00:32:45 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450657965708], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450657965686]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Validated
D/ConnectivityService(  853): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  853): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  853): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
D/ConnectivityService(  853): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1747): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1747):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  853): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiDataContinuityService(  853): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
,I/WifiServerServiceExt(  853): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  853): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/NotificationManager( 1937): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  853): identical MTU - not setting
D/Nat464Xlat(  853): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  853): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:46.438 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/dhcpcd  ( 6690): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
D/ConnectivityService(  853): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  853): enableDataServiceNotify 
D/DSQN    (  853): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524295
,D/DSQN    (  853): dsqn is running restart
I/dhcpcd  ( 6690): wlan0: leased 192.168.1.134 for 86400 seconds
,I/DSQN    ( 6722): DSQN samuel.seo ver 141203
E/DSQN    ( 6722): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6722): created command queue thread
I/DSQN    ( 6722): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6722): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  853): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  853): onReceive
D/LocSvc_java(  853): got connectivity action
D/LocSvc_java(  853): broadcast - no network connections
D/LocSvc_java(  853): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  853): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  853): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  853): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  853): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  853): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  853): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6746 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider(  853): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  853): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  853): onReceive
D/LocSvc_java(  853): got connectivity action
D/LocSvc_java(  853): broadcast - no network connections
D/LocSvc_java(  853): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  853): Sending msg: 4 arg1:0 arg2:1
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  853): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  853): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  853): ignore wifi update if we are not in OPENING or CLOSING
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  853): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  853): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  853): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  853): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  853): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  853): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  853): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  853): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  853): RunningState
I/MusicStore( 6746): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6746): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  853): Process com.google.android.gms:car (pid 6361) has died
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6746): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6746): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6746): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6746): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6746): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6746): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6746): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14bedae0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6746): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6746): GMSCore installation verified
I/ConfigStore( 6746): Config Database version: 1
,I/MediaRouter( 6746): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6746): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6746): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6746): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6787 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6746): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6746): Using platform SSLCertificateSocketFactory
I/NotificationManager( 6746): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6787): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6787): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6787): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/LGEmail ( 6787): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6787): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-21 01:32:47.862 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/eas_req ( 6787): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/WifiInternetCheck(  853): Single check msg out of sync, ignoring.
,D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6820 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/LocSvc_java(  853): onReceive
D/LocSvc_java(  853): got connectivity action
D/LocSvc_java(  853): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  853): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  853): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  853): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  853): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  853): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/NetworkMonitor( 6746): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider(  853): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/HubEmail( 6787): JNI_OnLoad()
I/HubEmail( 6787): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6787): registerNatives()
I/HubEmail( 6787): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6787): registerNativeMethods()
I/HubEmail( 6787): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6787): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6787): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  853): Process com.android.vending (pid 5716) has died
,D/LGDMClient( 6820): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6820): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6820): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6820): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6820): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6820): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 6820): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6820): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6850 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6820): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6820): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6820): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6820): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6820): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6820): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 6850): onCreate
,W/AppUp4:DB( 6850):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6850):  setFingerPrint start
I/AppUp4:DB( 6850):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6850):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6850):  SDK version = 0
I/AppUp4:DB( 6850):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6850): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6850): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6850): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6850): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6850): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6850): onReceive
,I/AppUp4:CustModeStarterReceiver( 6850): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6850): Context : android.app.ReceiverRestrictedContext@3b516884
D/AppUp4:CustFacade( 6850): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6850): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6850): begin check event
I/AppUp4:CustModeStarterReceiver( 6850): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 6850): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6850): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6850): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6850): handleAsyncCustNotification do not startCustService
I/ActivityManager(  853): Killing 6642:com.google.android.talk/u0a61 (adj 15): empty #11
D/BluetoothAdapterService(684195123)( 1963): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@316db1a1
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6435): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6435): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 6435): BLE supported!!
I/jxcore-log( 6435): 
W/libprocessgroup(  853): failed to open /acct/uid_10061/pid_6642/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3209): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3209): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3209): networkInfo.isConnected() = false
I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6873 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6873): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6873): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6873): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  853): Killing 6592:com.android.settings/1000 (adj 15): empty #11
D/PhoneMonitor( 6873): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6873): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6873): [parse] Load xml
V/TelephonyAutoProfiling( 6873): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6873): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6873): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6592/cgroup.procs: No such file or directory
,V/DownloadManager( 3230): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3230): DownloadService onCreate
,I/DownloadManager( 3230): in removeSpuriousFiles
I/NotificationManager( 3230): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@2fca8f8b on behalf of 3230
I/DownloadManager( 3230): in trimDatabase
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@217da868 on behalf of 3230
,I/CheckinService( 4265): Checkin interval check for package: unspecified last checkin: 1450657939162 min interval config: 0 actual interval: 29499
I/ActivityManager(  853): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6896 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/CheckinService( 4265): Checking schedule, now: 1450657968683 next: 1450657969124
I/CheckinService( 4265): active receiver: disabled
V/DownloadManager( 3230): DownloadService onStartCommand
,V/DownloadManager( 3230): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@17509967 on behalf of 3230
V/DownloadManager( 3230): DownloadService onDestroy
,I/ActivityManager(  853): Killing 5829:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5791): android.os.DeadObjectException
,W/System.err( 5791): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5791): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5791): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5791): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5791): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5791): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5791): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5791): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5791): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5791): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5791): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5791): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5791): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5791): android.os.DeadObjectException
W/System.err( 5791): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5791): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5791): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5791): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5791): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5791): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5791): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5791): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5791): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5791): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5791): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5791): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5791): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_5829/cgroup.procs: No such file or directory
W/ActivityManager(  853): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/WeatherAncestor( 2774): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:32:48
I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6914 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UpdateThreadPoolManager( 2774): 2 : This is isUpdating : false
D/WeatherAncestor( 2774): connectivity changed - connection : true
D/Weather_cast( 2774): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2774): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:32:48
,I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 23.744ms
D/WeatherService( 2774): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 35.580ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 19.903ms
,I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6939 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2774): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2774): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2774): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6939): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6914): Quickset Services start...
I/UEI.SmartControl( 6914): Manufacture = LGE
D/UEI.SmartControl( 6914): File observer start...
E/UEI.SmartControl( 6914): IR Port is disabled: false
,D/UEI.SmartControl( 6914): Starting file observer...
D/UEI.SmartControl( 6914): Extracting JNI libs...
D/UEI.SmartControl( 6914): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6914): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6914): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6914): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
I/UEI.SmartControl( 6914): --- Selecting new region: 2
I/UEI.SmartControl( 6914): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6914): Platform has CIR...
D/UEI.SmartControl( 6914): NO CIR support, need to check package...
I/UEI.SmartControl( 6914): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6914): QS Service created
I/Babel_SMS( 6939): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6939): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6939): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6939): MmsConfig.loadFromDatabase
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out(  853): propertyValue:false
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out(  853): propertyValue:false
E/UEI.SmartControl( 6914): QS start get config
I/DSQN    ( 6722): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6722): restart monitoring
I/DSQN    ( 6722): dsqn report finish
D/LGDataListener(  277): argv[0]=dsqncommand
D/LGDataListener(  277): argv[1]=wlan0
D/LGDataListener(  277): argv[2]=1
D/LGDataListener(  277): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  853): DSQM DsqnNotification wlan0  1
D/DSQN    (  853): start to monitor internet connection
,E/Babel_SMS( 6939): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6939): MmsConfig.loadFromResources
,V/WifiInternetCheck(  853): isHttpConnectionAvailable - We got a valid response : 204
E/Babel_SMS( 6939): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6939): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6939): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 6939): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6939): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6939): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6939): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6939): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6939): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6939): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6939): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6939): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6939): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6939): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6939): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6939): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6939): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6939): found sensor: Motion Accel, handle=46
D/UEI.SmartControl( 6914): Loading JNI Libs...
D/UEI.SmartControl( 6914):  configuring local db...
,W/Settings( 6939): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6939): startup - clean
I/Babel   ( 6939): deleted: false for 0
,I/art     ( 6939): CheckpointMarkThreadRoots callback created = 0xaaf418b0
,I/art     ( 6939): CheckpointMarkThreadRoots callback created = 0xaaf41890
,I/ActivityManager(  853): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6975 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 6939): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6939): Unsupported mime audio/adpcm
W/AudioCapabilities( 6939): Unsupported mime audio/g726
W/AudioCapabilities( 6939): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6939): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6939): Unsupported mime video/mjpg
,W/VideoCapabilities( 6939): Unsupported mime video/theora
W/AudioCapabilities( 6939): Unsupported mime audio/evrc
D/UEI.SmartControl( 6914):  ---- Has DB8: true
W/AudioCapabilities( 6939): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6939): Unrecognized profile 2130706433 for video/avc
D/UEI.SmartControl( 6914): QS start statue = true Error code = 0
,W/AudioCapabilities( 6939): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6939): Unsupported mime audio/qcelp
W/AudioCapabilities( 6939): Unsupported mime audio/evrc
,W/VideoCapabilities( 6939): Unsupported mime video/mp4v-esdp
,I/ActivityManager(  853): Process com.google.android.music:main (pid 6746) has died
I/VideoCapabilities( 6939): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6939): Unrecognized profile 2130706433 for video/avc
D/UEI.SmartControl( 6914): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6914): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
W/VideoCapabilities( 6939): Unrecognized profile 2130706433 for video/avc
D/UEI.SmartControl( 6914): IRRCDataComm has AudioManager!!!!.
W/VideoCapabilities( 6939): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6939): Unrecognized profile 2130706433 for video/avc
,W/irrc_jni( 6914): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6914): IrrcClient ++ 
D/irrcClient( 6914): getIrrcService ++ 
D/irrcClient( 6914): getIrrcService -- 
D/irrcClient( 6914): IrrcClient -- 
W/irrc_jni( 6914): IRRCPlayer_nativeInit -- 
I/vclib   ( 6939): onServiceConnected
,W/Babel   ( 6939): Attempted to change video mute state without an active call.
D/UEI.SmartControl( 6914): Services init done
D/UEI.SmartControl( 6914): QS Service init finished
D/UEI.SmartControl( 6914): QS Service version name: 0.1.73
D/UEI.SmartControl( 6914): QS Service version code: 1073
D/UEI.SmartControl( 6914): Service requested: Control
,I/UEI.SmartControl( 6914): Device manager: loading config....
I/NotificationManager( 6939): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6939): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6939): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6939): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6939): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 6939): propertyValue:false
D/UEI.SmartControl( 6914): Config is loaded...
D/UEI.SmartControl( 6914):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6914): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6914): Request IControl service: devices are loaded...
,I/Babel   ( 6939): connection state changed from UNKNOWN to CONNECTED
I/art     (  853): Explicit concurrent mark sweep GC freed 79533(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.369ms total 177.892ms
,I/ActivityManager(  853): Killing 6620:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6914): -----IControl: 11
D/UEI.SmartControl( 6914): Caller: com.lge.qremote
D/UEI.SmartControl( 6914): ------------ IControl registerCallback...
I/UEI.SmartControl( 6914): Registering callback...
D/UEI.SmartControl( 6914): -----IControl: 19
D/UEI.SmartControl( 6914): Caller: com.lge.qremote
I/UEI.SmartControl( 6914): Registering Services Ready callback...
I/UEI.SmartControl( 6914): Notify client services are ready...
D/UEI.SmartControl( 6914): -----IControl: 8
,D/UEI.SmartControl( 6914): Caller: com.lge.qremote
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6620/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6914): Internal service binding...
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6975): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6975): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6975): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6975): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6975): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6975):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6975):   adb logcat -s GAv4
,W/GAv4    ( 6975): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6975): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6975): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{3bcbeb0a type 2 when 110348 com.google.android.gms} when 110348
I/WebViewFactory( 6975): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6975): Time to load native libraries: 1 ms (timestamps 681-682)
I/LibraryLoader( 6975): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6975): Binding Chromium to main looper Looper (main, tid 1) {1e569ff1}
I/LibraryLoader( 6975): Expected native library version number "",actual native library version number ""
I/chromium( 6975): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6975): Initializing chromium process, singleProcess=true
,W/art     ( 6975): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6975): ApplicationContext is null in ApplicationStatus
W/chromium( 6975): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6975): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6975): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6975): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6975): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6975): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6975): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6975): Remote Branch: 
I/Adreno-EGL( 6975): Local Patches: 
I/Adreno-EGL( 6975): Reconstruct Branch: 
V/AudioPolicyService(  283): registerClient() client 0xb551c800, uid 10079
,W/AudioManagerAndroid( 6975): Requires BLUETOOTH permission
I/NSApplication( 6975): Starting up...
,I/ActivityManager(  853): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7050 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 5791:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10106/pid_5791/cgroup.procs: No such file or directory
,V/AlarmManager(  853): RTC_WAKEUP set : Alarm{930663f type 0 when 1450657969124 com.google.android.gms} when 1450657969124
,I/ActivityManager(  853): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7067 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{3c7ceb0c type 0 when 1450657970693 com.android.vending} when 1450657970693
,I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7086 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 7067): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ResourcesManager( 7086): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 7067): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7067): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7067): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7067): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@160f7bd on behalf of 7067
D/Ads     ( 7067): Skipping gmscore version check
,D/Finsky  ( 7067): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7067): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  853): Killing 6787:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10021/pid_6787/cgroup.procs: No such file or directory
,D/Finsky  ( 7067): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7067): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  853): Killing 6820:com.lge.lgdmsclient/1000 (adj 15): empty #11
,D/Finsky  ( 7067): [865] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6820/cgroup.procs: No such file or directory
D/Finsky  ( 7067): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  853): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7134 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 6850:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_6850/cgroup.procs: No such file or directory
,I/MusicStore( 7134): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7134): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7134): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7134): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7134): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7134): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7134): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7134): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7134): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14bedae0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7134): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7134): GMSCore installation verified
I/ConfigStore( 7134): Config Database version: 1
,I/MediaRouter( 7134): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7134): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7134): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7134): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7165 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7134): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7134): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  853): Killing 6873:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/ResourcesManager( 7165): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7165): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7165): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_6873/cgroup.procs: No such file or directory
,I/NotificationManager( 7134): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7165): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7165): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7165): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7196 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7165): JNI_OnLoad()
I/HubEmail( 7165): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7165): registerNatives()
I/HubEmail( 7165): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7165): registerNativeMethods()
I/HubEmail( 7165): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7165): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7165): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  853): Killing 6896:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10051/pid_6896/cgroup.procs: No such file or directory
,D/LGDMClient( 7196): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7196): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7196): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7196): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7196): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7196): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 7196): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7196): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7220 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7196): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7196): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7196): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7196): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7196): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{a4350ef type 0 when 1450657973055 com.google.android.googlequicksearchbox} when 1450657973055
,D/LGDMClient( 7196): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  853): Killing 6914:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,I/AppUp4:AppBoxCP( 7220): onCreate
,W/AppUp4:DB( 7220):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7220):  setFingerPrint start
I/AppUp4:DB( 7220):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7220):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7220):  SDK version = 0
I/AppUp4:DB( 7220):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_6914/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 7220): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7220): onReceive
I/AppUp4:CustModeStarterReceiver( 7220): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7220): Context : android.app.ReceiverRestrictedContext@3b516884
D/AppUp4:CustFacade( 7220): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7220): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7220): begin check event
I/AppUp4:CustModeStarterReceiver( 7220): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7220): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7220): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7220): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 7220): handleAsyncCustNotification do not startCustService
I/ActivityManager(  853): Killing 6939:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10061/pid_6939/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3209): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3209): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3209): networkInfo.isConnected() = false
I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7254 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7254): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7254): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7254): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  853): Killing 6975:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
D/PhoneMonitor( 7254): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,V/DownloadManager( 3230): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  853): failed to open /acct/uid_10079/pid_6975/cgroup.procs: No such file or directory
V/DownloadManager( 3230): DownloadService onCreate
I/NotificationManager( 3230): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/CheckinService( 4265): Checkin interval check for package: unspecified last checkin: 1450657939162 min interval config: 0 actual interval: 34319
V/TelephonyAutoProfiling( 7254): [loadFeatureFromXml] *** start feature loading from xml
I/DownloadManager( 3230): in removeSpuriousFiles
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@39436503 on behalf of 3230
D/TelephonyAutoProfiling( 7254): [parse] Load xml
I/DownloadManager( 3230): in trimDatabase
,V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/TelephonyAutoProfiling( 7254): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7254): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@dcb1c80 on behalf of 3230
,D/PhoneMonitor( 7254): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  853): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7283 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3230): DownloadService onStartCommand
I/CheckinService( 4265): Checking schedule, now: 1450657973524 next: 1450657969124
I/CheckinService( 4265): active receiver: enabled
V/DownloadManager( 3230): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 342us total 27.582ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 25.379ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 22.239ms
,I/CheckinService( 4265): Preparing to send checkin request
I/EventLogService( 4265): Accumulating logs since 1450657931106
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@344fc6fe on behalf of 3230
,D/WeatherAncestor( 2774): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:32:53
D/UpdateThreadPoolManager( 2774): 2 : This is isUpdating : false
D/WeatherAncestor( 2774): connectivity changed - connection : true
D/Weather_cast( 2774): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2774): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:32:53
D/WeatherService( 2774): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7310 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2774): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2774): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2774): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/DownloadManager( 3230): DownloadService onDestroy
I/CheckinRequestBuilder( 4265): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4265): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  853): Explicit concurrent mark sweep GC freed 23585(1214KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.044ms total 149.393ms
,W/ResourcesManager( 7310): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  853): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7332 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/Babel_SMS( 7310): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7310): MmsConfig.loadMmsSettings
I/Babel_SMS( 7310): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7310): MmsConfig.loadFromDatabase
W/ResourcesManager( 7332): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7332): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Babel_SMS( 7310): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7310): MmsConfig.loadFromResources
,E/Babel_SMS( 7310): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7310): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7310): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7310): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7310): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7310): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7310): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7310): found sensor: LGE Linear Acceleration Sensor, handle=30
,D/SensorManager( 7310): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7310): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7310): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7310): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7310): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7310): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7310): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7310): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7310): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7310): found sensor: Motion Accel, handle=46
W/Settings( 7310): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7310): startup - clean
I/Babel   ( 7310): deleted: false for 0
,I/MultiDex( 7332): VM with version 2.1.0 has multidex support
I/MultiDex( 7332): install
I/MultiDex( 7332): VM has multidex support, MultiDex support library is disabled.
,I/art     ( 7310): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/art     ( 7310): CheckpointMarkThreadRoots callback created = 0xb042d880
,I/ActivityManager(  853): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7360 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 7310): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7310): Unsupported mime audio/adpcm
W/AudioCapabilities( 7310): Unsupported mime audio/g726
,W/AudioCapabilities( 7310): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7310): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7310): Unsupported mime video/mjpg
V/JNIHelp ( 7332): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/VideoCapabilities( 7310): Unsupported mime video/theora
W/AudioCapabilities( 7310): Unsupported mime audio/evrc
W/AudioCapabilities( 7310): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7310): Unsupported mime audio/amr-wb-plus
W/ActivityThread( 7332): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/AudioCapabilities( 7310): Unsupported mime audio/qcelp
W/System  ( 7332): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34409481: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7332): Installed default security provider GmsCore_OpenSSL
W/AudioCapabilities( 7310): Unsupported mime audio/evrc
I/NotificationManager( 7332): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7332): com.google.android.gms: cancel(39789) by com.google.android.gms
,W/VideoCapabilities( 7310): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7310): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 114758463762; DSPS: 3851738; Offset : -2796177221
,W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7310): onServiceConnected
W/Babel   ( 7310): Attempted to change video mute state without an active call.
,I/NotificationManager( 7310): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/art     ( 7332): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7332): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/libc-netbsd( 7310): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7310): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7310): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7310): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 7310): propertyValue:false
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,I/Babel   ( 7310): connection state changed from UNKNOWN to CONNECTED
W/ContextImpl( 7360): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/ActivityManager(  853): Killing 7050:com.android.chrome/u0a48 (adj 15): empty #11
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 7360): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7360):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7360):   adb logcat -s GAv4
W/ContextImpl( 7360): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7360): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7360): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/NativeLibraryUtils( 7332): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  853): failed to open /acct/uid_10048/pid_7050/cgroup.procs: No such file or directory
,W/GAv4    ( 7360): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/WVCdm   (  283): Instantiating CDM.
I/WVCdm   (  283): CdmEngine::OpenSession
,I/WVCdm   (  283): Level3 Library Dec 11 2014 16:13:16
W/GAv4    ( 7360): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7360): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  283): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  283): L1 library not specified. Falling Back to L3
I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=1903121244
I/WebViewFactory( 7360): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7360): Time to load native libraries: 1 ms (timestamps 5389-5390)
I/LibraryLoader( 7360): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7360): Binding Chromium to main looper Looper (main, tid 1) {1e569ff1}
I/LibraryLoader( 7360): Expected native library version number "",actual native library version number ""
I/chromium( 7360): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7360): Initializing chromium process, singleProcess=true
,I/art     ( 7332): CheckpointMarkThreadRoots callback created = 0xb042d8c0
W/art     ( 7360): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7360): ApplicationContext is null in ApplicationStatus
W/chromium( 7360): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7360): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7360): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7360): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7360): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7360): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7360): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7360): Remote Branch: 
I/Adreno-EGL( 7360): Local Patches: 
I/Adreno-EGL( 7360): Reconstruct Branch: 
I/art     ( 7332): CheckpointMarkThreadRoots callback created = 0xb042d8b0
,I/NSApplication( 7360): Starting up...
,V/AudioPolicyService(  283): registerClient() client 0xb551cba0, uid 10079
W/AudioManagerAndroid( 7360): Requires BLUETOOTH permission
I/ActivityManager(  853): Process com.google.android.music:main (pid 7134) has died
,I/ActivityManager(  853): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7430 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7067:com.android.vending/u0a36 (adj 15): empty #11
,I/dex2oat ( 7447): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  853): failed to open /acct/uid_10036/pid_7067/cgroup.procs: No such file or directory
,I/dex2oat ( 7447): dex2oat took 101.132ms (threads: 4)
,I/Adreno-EGL( 7332): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7332): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7332): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7332): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7332): Remote Branch: 
I/Adreno-EGL( 7332): Local Patches: 
I/Adreno-EGL( 7332): Reconstruct Branch: 
,I/ActivityManager(  853): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7455 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Adreno-EGL( 7332): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7332): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7332): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7332): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7332): Remote Branch: 
I/Adreno-EGL( 7332): Local Patches: 
I/Adreno-EGL( 7332): Reconstruct Branch: 
,I/MusicStore( 7455): Database version: 120
,I/Adreno-EGL( 7332): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7332): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7332): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7332): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7332): Remote Branch: 
I/Adreno-EGL( 7332): Local Patches: 
I/Adreno-EGL( 7332): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7455): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7455): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7455): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/WVCdm   (  283): CdmEngine::OpenSession
,W/ResourcesManager( 7455): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7455): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7455): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7455): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7455): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14bedae0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7455): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7455): GMSCore installation verified
I/ConfigStore( 7455): Config Database version: 1
,I/art     ( 6288): Explicit concurrent mark sweep GC freed 2078(90KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 379us total 25.848ms
,I/MediaRouter( 7455): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7455): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7455): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7455): type=WIFI subType= reason=null isConnected=true
,D/LGDMClient( 7196): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7196): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7196): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7196): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/Settings( 7165): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] request level :IDLE....
,D/LGDMClient( 7196): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/AppUp4:CustModeStarterReceiver( 7220): onReceive
I/AppUp4:CustModeStarterReceiver( 7220): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7220): Context : android.app.ReceiverRestrictedContext@3b516884
D/AppUp4:CustFacade( 7220): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7220): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7220): begin check event
I/AppUp4:CustModeStarterReceiver( 7220): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/LgeMiscReceiver( 3209): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3209): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3209): networkInfo.isConnected() = true
,I/LGDMClient( 7196): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 7196): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7196): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/PhoneState( 3209): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 7254): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7254): onReceive CONNECTIVITY_CHANGE networkType=1
W/ContextImpl( 7196): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3230): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,E/LGDMClient( 7196): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
V/DownloadManager( 3230): DownloadService onCreate
D/LGDMClient( 7196): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7196): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/WeatherAncestor( 2774): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:32:56
D/LGDMClient( 7196): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/NotificationManager( 3230): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3230): in removeSpuriousFiles
,V/DownloadManager( 3230): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/UpdateThreadPoolManager( 2774): 2 : This is isUpdating : false
D/WeatherAncestor( 2774): connectivity changed - connection : true
D/Weather_cast( 2774): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2774): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:32:56
D/WeatherService( 2774): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@2f0580ac on behalf of 3230
D/LGDMClient( 7196): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/GHttpClientFactory( 7455): Using our fixed implementation of GMSCore's GoogleHttpClient
I/DownloadManager( 3230): in trimDatabase
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2774): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@315d550a on behalf of 3230
I/GoogleURLConnFactory( 7455): Using platform SSLCertificateSocketFactory
,D/WeatherService( 2774): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2774): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/DownloadManager( 3230): DownloadService onStartCommand
V/DownloadManager( 3230): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@1c9ffb98 on behalf of 3230
V/DownloadManager( 3230): DownloadService onDestroy
,I/ActivityManager(  853): Killing 7455:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10081/pid_7455/cgroup.procs: No such file or directory
,W/ActivityManager(  853): Unbind failed: could not find connection for android.os.BinderProxy@2ee80f4e
D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  853): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7505 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/MusicWidget( 2699): mDelayedStopHandler : unbind
,W/ResourcesManager( 7505): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/MusicBrowser( 2804): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2804): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2804): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2804): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2804): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2804): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2804): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2804): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  853):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2192c6ddcom.lge.music.MediaPlaybackService$6@30043252
,D/MusicBrowser( 2804): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2804): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2804): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2804): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2804): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@14be88f0
I/MusicBrowser( 2804): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2804): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
,I/MusicBrowser( 2804): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2804): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2804): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2804): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2804): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2804): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2804): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2804): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2804): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2804): [MediaPlaybackService.java:6745:release()] oooooo 
,I/MusicBrowser( 2804): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2804): reset
I/WVCdm   (  283): CdmEngine::CloseSession
V/MediaPlayer[Native]( 2804): setListener
V/MediaPlayer[Native]( 2804): disconnect
,V/MediaPlayer[Native]( 2804): destructor
V/AudioFlinger(  283): releasing 18 from 2804 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/MediaPlayer[Native]( 2804): disconnect
D/MusicBrowser( 2804): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6b2ba26:true
I/SmartShareClient( 2804): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2804): [SmartShareManagerClient] smartshare client enabled
D/BluetoothAdapterService(684195123)( 1963): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@316db1a1
I/MusicBrowser( 2804): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2804): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2804): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2804): [SmartShareManagerClient] unregisterListener: 915052835
W/SmartShareClient( 2804): [SmartShareManagerClient] unregisterListener invalid listener: 915052835
I/SmartShareClient( 2804): [SmartShareManagerClient] terminate service: 2804/MediaPlaybackService/1035470102
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/BluetoothAdapterService(684195123)( 1963): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@316db1a1
E/HomeCloudIF( 2804): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2804): [SmartShareManagerClient] unbindService context:android.app.Application@7be0e20
V/CloudHub( 2804): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2804): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2804): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2804): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2804): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  853): Killing 7165:com.lge.email/u0a21 (adj 15): empty #11
I/CloudHub( 2804): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29988
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=1819271137
W/libprocessgroup(  853): failed to open /acct/uid_10021/pid_7165/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7532 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7505): Create singleton instance
,D/UEI.SmartControl( 7532): Quickset Services start...
,I/UEI.SmartControl( 7532): Manufacture = LGE
I/AudioManager( 7505): getMode name:com.lge.qremote
D/UEI.SmartControl( 7532): File observer start...
E/UEI.SmartControl( 7532): IR Port is disabled: false
D/UEI.SmartControl( 7532): Starting file observer...
D/UEI.SmartControl( 7532): Extracting JNI libs...
D/UEI.SmartControl( 7532): --- this system supports 32-bit or 64-bit only
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
I/CheckinService( 4265): Checkin interval check for package: unspecified last checkin: 1450657939162 min interval config: 0 actual interval: 38146
,D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1729): propertyValue:false
W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/UEI.SmartControl( 7532): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7532): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7532): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/UEI.SmartControl( 7532): --- Selecting new region: 2
I/UEI.SmartControl( 7532): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7532): Platform has CIR...
D/UEI.SmartControl( 7532): NO CIR support, need to check package...
I/UEI.SmartControl( 7532): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7532): QS Service created
,I/art     (  853): Explicit concurrent mark sweep GC freed 15864(726KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.919ms total 185.123ms
,D/WearableService( 1729): callingUid 10006, callindPid: 1729
D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4265): Restart initialization of location
,E/MDM     ( 1729): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 7505): getMode name:com.lge.qremote
W/GCoreFlp( 1729): No location to return for getLastLocation()
W/FusedLocationProvider( 1729): location=null
,E/UEI.SmartControl( 7532): QS start get config
,D/UEI.SmartControl( 7532): Loading JNI Libs...
D/UEI.SmartControl( 7532):  configuring local db...
D/UEI.SmartControl( 7532):  ---- Has DB8: true
,D/UEI.SmartControl( 7532): QS start statue = true Error code = 0
D/UEI.SmartControl( 7532): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7532): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7532): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7532): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 7532): IrrcClient ++ 
D/irrcClient( 7532): getIrrcService ++ 
D/irrcClient( 7532): getIrrcService -- 
D/irrcClient( 7532): IrrcClient -- 
W/irrc_jni( 7532): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7532): Services init done
I/UEI.SmartControl( 7532): Device manager: loading config....
D/UEI.SmartControl( 7532): QS Service init finished
D/UEI.SmartControl( 7532): QS Service version name: 0.1.73
D/UEI.SmartControl( 7532): Config is loaded...
D/UEI.SmartControl( 7532): QS Service version code: 1073
D/UEI.SmartControl( 7532): Service requested: Control
,D/UEI.SmartControl( 7532): Internal service binding...
D/UEI.SmartControl( 7532): -----IControl: 11
D/UEI.SmartControl( 7532): Caller: com.lge.qremote
D/UEI.SmartControl( 7532): ------------ IControl registerCallback...
I/UEI.SmartControl( 7532): Registering callback...
D/UEI.SmartControl( 7532): -----IControl: 19
D/UEI.SmartControl( 7532): Caller: com.lge.qremote
I/UEI.SmartControl( 7532): Registering Services Ready callback...
D/UEI.SmartControl( 7532):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7532): Notify AllClients services are ready: 0
I/UEI.SmartControl( 7532): Notify client services are ready...
,D/UEI.SmartControl( 7532): -----IControl: 8
D/UEI.SmartControl( 7532): Caller: com.lge.qremote
I/AudioManager( 7505): getMode name:com.lge.qremote
I/ActivityManager(  853): Killing 7196:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/ActivityManager(  853): Killing 7220:com.lge.appbox.client/u0a11 (adj 15): empty #12
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_7196/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_7220/cgroup.procs: No such file or directory
I/AudioManager( 7505): getMode name:com.lge.qremote
I/AudioManager( 7505): getMode name:com.lge.qremote
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): L3 Terminate.
D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=424594530, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,D/WeatherService( 2774): 2 : TimeTick Intent has been received, Time(hour:min:sec) 1:33:0
,D/WeatherService( 2774): 2 : TimeTick Intent And Screen On
D/WeatherService( 2774): 2 : SDK version : 21
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2774): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2774): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2774): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2774): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2774): 2 : This is isUpdating : false
D/WeatherService( 2774): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2774): 2 : buildUpdate, appWidgetId: 2
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/WeatherTheme( 2774): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2774): 2 : Fixed theme : optimus
D/WeatherReflect( 2774): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,D/lim     ( 2774): 2 : time = 01:33
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/WeatherReflect( 2774): Model Name : LG-D722
D/WeatherTheme( 2774): 2 : Different view - status_min_formatted : 32 != 33
D/WeatherTheme( 2774): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/WeatherReflect( 2774): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2774): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2774): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2774): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2774): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
,D/Weather4x2_optimus( 2774): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2774): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2774): forecast size is 0
,D/Theme   ( 2774): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2774): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2774): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2774): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2774): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2774): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2774): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2774): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2774): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2774): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2774): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2774): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2774): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2774): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2774): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2774): url is : null
D/Theme   ( 2774): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2774): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2774): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2774): 2 : update view, appWidgetId: 2
D/WeatherService( 2774): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 1:33:0
,D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=424594530 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/CheckinRequestBuilder( 4265): Classify the device as Phone.
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/libc-netbsd( 4265): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4265): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4265): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4265): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 4265): propertyValue:false
,D/libc-netbsd( 4265): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4265): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4265): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4265): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4265): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4265): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4265): Sending checkin request (9697 bytes)
,I/CheckinRequestBuilder( 4265): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4265): Failed to find provider info for com.google.android.wearable.settings
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 7086): CheckpointMarkThreadRoots callback created = 0xaaec4af0
,I/art     ( 7086): CheckpointMarkThreadRoots callback created = 0xaaec45c0
I/CheckinRequestBuilder( 4265): Classify the device as Phone.
I/CheckinTask( 4265): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4265): Checking schedule, now: 1450657981200 next: 1451185230194
I/CheckinService( 4265): active receiver: disabled
,I/CheckinService( 4265): Checking schedule, now: 1450657981229 next: 1451185230194
I/CheckinService( 4265): active receiver: disabled
,D/CheckinService( 4265): Recording last checkin time for package unspecified as 1450657981240
V/SetupWizard( 7254): Connected to Gservices successfully
,D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{f9a4386 type 2 when 122589 com.google.android.gms} when 122589
,I/ActivityManager(  853): Killing 7360:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/ActivityManager(  853): Killing 7283:com.lge.drmservice/u0a51 (adj 15): empty #12
,W/libprocessgroup(  853): failed to open /acct/uid_10079/pid_7360/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10051/pid_7283/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7532): Internal timer expired: 1
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 7310): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7310): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/NotificationManager( 7310): com.google.android.talk: cancel(8) by com.google.android.talk
V/JNIHelp ( 7310): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7634 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/administrator(  853): Handling package changes for user 0
W/System  ( 7310): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7310): Installed default security provider GmsCore_OpenSSL
,I/AppUp4:AppBoxCP( 7634): onCreate
W/AppUp4:DB( 7634):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7634):  setFingerPrint start
I/AppUp4:DB( 7634):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7634):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7634):  SDK version = 0
,I/AppUp4:DB( 7634):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7634): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7634): onReceive
,I/AppUp4:CustModeStarterReceiver( 7634): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7634): Context : android.app.ReceiverRestrictedContext@23a2da31
D/AppUp4:CustFacade( 7634): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7634): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7634): begin check event
I/AppUp4:CustModeStarterReceiver( 7634): Event For Nothing, skip.
I/NotificationService(  853): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  853): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  853): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7657 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/BackupManagerService(  853): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  853): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  853): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@275d9459
,W/ResourcesManager( 7657): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7657): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7657): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
,W/ResourceType(  853): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1729): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppConfig( 7657): Total System Memory = 906309632
I/GalleryUtils( 7657): Application Heap = 96 MB
I/AppConfig( 7657): App Tier : NOT_DEF
,D/LocationProviderProxy(  853): applying state to connected service
,D/SystemHelper( 7657): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  853): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7677 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7430:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10048/pid_7430/cgroup.procs: No such file or directory
,W/ResourcesManager( 7677): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7677): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7677): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7677): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7677): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 7677): BUILD Country: EU
I/SystemConfig( 7677): BUILD Operator: OPEN
,I/ActivityManager(  853): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7703 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7086:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.106ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 22.530ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.700ms
,W/libprocessgroup(  853): failed to open /acct/uid_10086/pid_7086/cgroup.procs: No such file or directory
I/SystemConfig( 7677): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7677): existFile = false
,I/SystemConfig( 7677): canReadFile = false
I/SystemConfig( 7677): systemFeature RCS result false
D/SystemConfig( 7677): refreshRcsSupport() :false
I/LockScreenSettings( 7703): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7703): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7703): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7703): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7703): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7703): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7720 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 2804:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  283): 2804 died, releasing its sessions
V/AudioFlinger(  283):  pid 1747 @ 0
V/AudioFlinger(  283):  pid 3209 @ 1
V/AudioFlinger(  283):  pid 3209 @ 2
,W/libprocessgroup(  853): failed to open /acct/uid_10028/pid_2804/cgroup.procs: No such file or directory
,W/ResourcesManager( 7720): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  853): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7745 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7254:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 98 ms] updated apps [took 97 ms] 
,W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_7254/cgroup.procs: No such file or directory
,D/Finsky  ( 7745): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7745): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7745): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7745): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7745): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@3503b7d6 on behalf of 7745
D/Finsky  ( 7745): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7745): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7745): Skipping gmscore version check
D/Finsky  ( 7745): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4265): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4265): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7745): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4265): updateResources: need to parse f{com.google.android.gms}
,I/art     (  853): Explicit concurrent mark sweep GC freed 30518(1520KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.482ms total 155.125ms
,D/charger_monitor(  488): init target 500000
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 298, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/Icing   ( 4265): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4265): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  853): Killing 7332:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10006/pid_7332/cgroup.procs: No such file or directory
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/ActivityManager(  853): Killing 7532:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7505): android.os.DeadObjectException
,W/System.err( 7505): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7505): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7505): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7505): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7505): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7505): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7505): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7505): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7505): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7505): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7505): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7505): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7505): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7505): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7505): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7505): android.os.DeadObjectException
W/System.err( 7505): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7505): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7505): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7505): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7505): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7505): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7505): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7505): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7505): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7505): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7505): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7505): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7505): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7505): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7505): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_7532/cgroup.procs: No such file or directory
W/ActivityManager(  853): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7801 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7801): Quickset Services start...
,I/UEI.SmartControl( 7801): Manufacture = LGE
D/UEI.SmartControl( 7801): File observer start...
E/UEI.SmartControl( 7801): IR Port is disabled: false
D/UEI.SmartControl( 7801): Starting file observer...
D/UEI.SmartControl( 7801): Extracting JNI libs...
D/UEI.SmartControl( 7801): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7801): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7801): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7801): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7801): --- Selecting new region: 2
,I/UEI.SmartControl( 7801): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7801): Platform has CIR...
D/UEI.SmartControl( 7801): NO CIR support, need to check package...
I/UEI.SmartControl( 7801): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7801): QS Service created
E/UEI.SmartControl( 7801): QS start get config
,D/UEI.SmartControl( 7801): Loading JNI Libs...
,D/UEI.SmartControl( 7801):  configuring local db...
D/UEI.SmartControl( 7801):  ---- Has DB8: true
,D/UEI.SmartControl( 7801): QS start statue = true Error code = 0
D/UEI.SmartControl( 7801): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7801): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7801): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7801): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7801): IrrcClient ++ 
D/irrcClient( 7801): getIrrcService ++ 
,D/irrcClient( 7801): getIrrcService -- 
D/irrcClient( 7801): IrrcClient -- 
W/irrc_jni( 7801): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7801): Services init done
I/UEI.SmartControl( 7801): Device manager: loading config....
D/UEI.SmartControl( 7801): QS Service init finished
D/UEI.SmartControl( 7801): QS Service version name: 0.1.73
D/UEI.SmartControl( 7801): QS Service version code: 1073
D/UEI.SmartControl( 7801): Service requested: Control
,D/UEI.SmartControl( 7801): Config is loaded...
D/UEI.SmartControl( 7801): Request IControl service: devices are loaded...
,I/ActivityManager(  853): Killing 7505:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7801): Internal service binding...
W/libprocessgroup(  853): failed to open /acct/uid_10106/pid_7505/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7801):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7801): Notify AllClients services are ready: 0
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 134760259641; DSPS: 4507157; Offset : -2796182712
,D/UEI.SmartControl( 7801): Internal timer expired: 1
,D/UEI.SmartControl( 7801): Service.onUnbind: IControl
D/UEI.SmartControl( 7801): Service.onDestroy
D/UEI.SmartControl( 7801): Shutdown IRRCPlayer... 
,W/irrc_jni( 7801): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7801): ~IrrcClient ++ 
D/irrcClient( 7801): ~IrrcClient -- 
W/irrc_jni( 7801): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7801): Blaster closed
D/UEI.SmartControl( 7801): Blaster closed
D/UEI.SmartControl( 7801): Shut down QS...
,D/UEI.SmartControl( 7801): Stopped file observer...
I/UEI.SmartControl( 7801): QS lib stop result = true
D/UEI.SmartControl( 7801): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{2491ef92 type 2 when 139979 com.google.android.gms} when 139979
,I/GoogleURLConnFactory( 1729): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PhenotypeConfigurator( 1729): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     ( 1729): Explicit concurrent mark sweep GC freed 41220(2MB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 13MB/22MB, paused 1.560ms total 152.465ms
,I/VacuumService( 1729): Vacuum at: now=1450658000270 tag=VacuumService
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 1729): propertyValue:false
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/PhenotypeConfigurator( 1729): Server returned 404
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (30911 ms ago)
,D/qdlights(  853): set_light_backlight: 254
,D/qdlights(  853): set_light_backlight: 251
D/qdlights(  853): set_light_backlight: 248
,D/qdlights(  853): set_light_backlight: 244
,D/qdlights(  853): set_light_backlight: 241
,D/qdlights(  853): set_light_backlight: 238
,D/qdlights(  853): set_light_backlight: 234
,D/qdlights(  853): set_light_backlight: 231
,D/qdlights(  853): set_light_backlight: 228
,D/qdlights(  853): set_light_backlight: 224
,D/qdlights(  853): set_light_backlight: 221
,D/qdlights(  853): set_light_backlight: 218
,D/qdlights(  853): set_light_backlight: 214
,D/qdlights(  853): set_light_backlight: 211
,D/qdlights(  853): set_light_backlight: 208
,D/qdlights(  853): set_light_backlight: 204
,D/qdlights(  853): set_light_backlight: 201
,D/qdlights(  853): set_light_backlight: 198
,D/qdlights(  853): set_light_backlight: 194
,D/qdlights(  853): set_light_backlight: 191
,D/qdlights(  853): set_light_backlight: 188
,D/qdlights(  853): set_light_backlight: 184
,D/qdlights(  853): set_light_backlight: 181
,D/qdlights(  853): set_light_backlight: 178
,D/qdlights(  853): set_light_backlight: 174
,D/qdlights(  853): set_light_backlight: 171
,D/qdlights(  853): set_light_backlight: 168
,D/qdlights(  853): set_light_backlight: 164
,D/qdlights(  853): set_light_backlight: 161
,D/qdlights(  853): set_light_backlight: 158
,D/qdlights(  853): set_light_backlight: 154
,D/qdlights(  853): set_light_backlight: 151
,D/qdlights(  853): set_light_backlight: 148
,D/qdlights(  853): set_light_backlight: 144
,D/qdlights(  853): set_light_backlight: 141
,D/qdlights(  853): set_light_backlight: 138
,D/qdlights(  853): set_light_backlight: 134
,D/qdlights(  853): set_light_backlight: 131
,D/qdlights(  853): set_light_backlight: 128
,D/qdlights(  853): set_light_backlight: 124
,D/qdlights(  853): set_light_backlight: 121
,D/qdlights(  853): set_light_backlight: 118
,D/qdlights(  853): set_light_backlight: 114
,D/qdlights(  853): set_light_backlight: 111
,D/qdlights(  853): set_light_backlight: 108
,D/qdlights(  853): set_light_backlight: 104
,D/qdlights(  853): set_light_backlight: 101
,D/qdlights(  853): set_light_backlight: 98
,D/qdlights(  853): set_light_backlight: 94
,D/qdlights(  853): set_light_backlight: 91
,D/qdlights(  853): set_light_backlight: 88
,D/qdlights(  853): set_light_backlight: 84
,D/qdlights(  853): set_light_backlight: 81
,D/qdlights(  853): set_light_backlight: 78
,D/qdlights(  853): set_light_backlight: 74
,D/qdlights(  853): set_light_backlight: 71
,D/qdlights(  853): set_light_backlight: 68
,D/qdlights(  853): set_light_backlight: 64
,D/qdlights(  853): set_light_backlight: 61
,D/qdlights(  853): set_light_backlight: 58
,D/qdlights(  853): set_light_backlight: 54
,D/qdlights(  853): set_light_backlight: 51
,D/qdlights(  853): set_light_backlight: 48
,D/qdlights(  853): set_light_backlight: 44
,D/qdlights(  853): set_light_backlight: 41
,D/qdlights(  853): set_light_backlight: 38
,D/qdlights(  853): set_light_backlight: 34
,D/qdlights(  853): set_light_backlight: 31
,D/qdlights(  853): set_light_backlight: 28
,D/qdlights(  853): set_light_backlight: 24
,D/qdlights(  853): set_light_backlight: 21
,D/qdlights(  853): set_light_backlight: 18
,D/qdlights(  853): set_light_backlight: 14
,D/qdlights(  853): set_light_backlight: 11
,D/qdlights(  853): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 154761357238; DSPS: 5162553; Offset : -2796183409
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (37901 ms ago)
I/PowerManagerService(  853): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (37915 ms ago)
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  853): Sleeping (uid 1000)...
D/LPWGController(  853): [updateScreenState] screen on = false
,D/LPWGController(  853): disable proximity sensor
D/LPWGController(  853): enable proximity sensor
,I/SensorManager(  853): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1b546389] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  853): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  853): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  853): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  853): activate: handle is 48, enable
,V/sensors_hal_Ctx(  853): activate sensors is 1400000000000
D/sensors_hal_Thresh(  853): enable: handle=48
I/sensors_hal_SAM(  853): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  853): waitForResponse: timeout=1000
V/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  853): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  853): enable: Received response: 0
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (37984 ms ago)
,I/Adreno-EGL(  853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  853): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  853): Build Date: 03/02/15 Mon
I/Adreno-EGL(  853): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  853): Remote Branch: 
I/Adreno-EGL(  853): Local Patches: 
I/Adreno-EGL(  853): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (144 us)
,I/Sensors (  433): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
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
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  853): set_light_backlight: 0
,I/SensorManager(  853): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  853): activate: handle is 46, disable
V/sensors_hal_Ctx(  853): activate sensors is 1000000000000
D/sensors_hal_LP2(  853): enable: handle=46
D/sensors_hal_LP2(  853): enable: Disabling sensor handle=46
,I/sensors_hal_SAM(  853): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  853): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  853): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  853): Display changed displayId=0
,D/DSDPConnection( 1747): Display #0 changed.
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  853): Excessive delay in setPowerMode(): 226ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  853): Got set_interactive hint
D/KeyguardViewMediator( 1371): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1371): notifyScreenOffLocked
D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
D/KeyguardViewMediator( 1371): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1371): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1371): unregisterProximitySensor
,D/StatusBarWindowView( 1371): onScreenTurnedOff why = 3
D/WifiServerServiceExt(  853): sendKtScanInterval  mRtspPlay : false
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=on, calling pid 853
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: enter: screen_state=on
,V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
,V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  283): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
I/WifiServerServiceExt(  853): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/GpsLocationProvider(  853): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:true
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1801): lockStatus = 0
D/LEDService( 1801): stopPatternFlashing()
D/LNfcService( 1783): action : android.intent.action.SCREEN_ON
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): updateLightsLocked : turn off led
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
,D/LEDHandler( 1801): RESTART MSG
D/NfcServiceNXP( 1783): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1783): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1783): isRequireNfcCRouting() return true
D/LNfcService( 1783): isHCERoutingtoHost() return : true
D/NfcService( 1783): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): newParams.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): screenState= 3
D/NfcService( 1783): Discovery configuration equal, not updating.
D/Ulp_jni (  853): JNI:system_update. Event-0
D/SplitWindow(  853): check instance of lgWin Window{cac23bc u0 SearchPanel}
,D/InputDispatcher(  853): Window went away: Window{349bbdc1 u0 SearchPanel}
,I/[SystemUI]Clock( 1371): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1371): time changed, timezoneChanged : false
,V/PhoneApp( 1747): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2774): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:33:39
,D/WeatherService( 2774): 2 : ACTION screen on
D/WeatherService( 2774): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2774): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2774): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:33:39
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): ACTION_SCREEN_ON
D/AppCleanupService( 4125): android.intent.action.SCREEN_ON
,V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=off, calling pid 853
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
,D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
D/WifiController(  853): CMD_SCREEN_OFF 
D/WifiController(  853): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  853): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:false
,I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1801): clear
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1783): action : android.intent.action.SCREEN_OFF
I/LEDService( 1801): updateLightsLocked : turn on led
E/LEDService( 1801): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1801): Can't handle this request of patternId:0
D/LEDHandler( 1801): RESTART MSG
D/NfcServiceNXP( 1783): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1874): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1747): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,I/Sensors (  433): sns_pwr.c(301):releasing wakelock
D/WeatherService( 2774): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:33:39
D/WeatherService( 2774): 2 : ACTION screen off
D/WeatherService( 2774): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2774): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:33:39
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): ACTION_SCREEN_OFF
D/AppCleanupService( 4125): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4125): AppUsageStatsSaveTask
,E/NxpNfcJni( 1783): getReconnectState = 0x0
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1783): getDefaultRoute
D/LNfcService( 1783): isRequireNfcCRouting() return true
D/LNfcService( 1783): isHCERoutingtoHost() return : true
D/NfcService( 1783): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): newParams.techmask= mTechMask: 0
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): screenState= 1
E/NxpNfcJni( 1783): getReconnectState = 0x0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  488): init target 500000
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 297, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1371): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{3796af45 type 2 when 163843 com.android.systemui} when 163843
,D/PhoneUtils( 1747): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1747): getCallState : 0
,D/PhoneUtils( 1747): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1371): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1371): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 174762515823; DSPS: 5817951; Offset : -2796184283
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  488): init target 500000
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=424594530, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{28edd69a type 2 when 189727 com.google.android.gms} when 189727
D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=424594530 [*alarm*], flags=0x0
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{39c37bcb type 2 when 191543 android} when 191543
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 194769232743; DSPS: 6473531; Offset : -2796180971
I/ClearcutLoggerApiImpl( 1729): disconnect managed GoogleApiClient
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 214769977162; DSPS: 7128915; Offset : -2796169442
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 234772004864; DSPS: 7784342; Offset : -2796186131
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  488): init target 500000
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 254773093032; DSPS: 8439737; Offset : -2796166416
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 274774580577; DSPS: 9095146; Offset : -2796174078
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 294776820672; DSPS: 9750580; Offset : -2796192205
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  488): init target 500000
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 314778691655; DSPS: 10406001; Offset : -2796182873
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 334780650553; DSPS: 11061425; Offset : -2796176943
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/LocationManagerService(  853): remove 4a691f5
D/LocationManagerService(  853): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  853): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  853): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  853): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=424594530, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=424594530 [*alarm*], flags=0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 354782055286; DSPS: 11716831; Offset : -2796176305
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 374784075435; DSPS: 12372257; Offset : -2796169926
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 394785190998; DSPS: 13027654; Offset : -2796183722
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 414786686825; DSPS: 13683063; Offset : -2796183307
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 434788937911; DSPS: 14338497; Offset : -2796190549
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 454790543007; DSPS: 14993909; Offset : -2796172210
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 474792414876; DSPS: 15649331; Offset : -2796192691
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 494794343201; DSPS: 16304754; Offset : -2796186583
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 514795978298; DSPS: 16960167; Offset : -2796169387
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 534797504070; DSPS: 17615577; Offset : -2796169129
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 554799385991; DSPS: 18270999; Offset : -2796179324
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 574801737286; DSPS: 18926436; Offset : -2796178377
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 594804272016; DSPS: 19581879; Offset : -2796176398
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 614806096748; DSPS: 20237299; Offset : -2796182747
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 634807973564; DSPS: 20892720; Offset : -2796167190
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 654810682620; DSPS: 21548169; Offset : -2796173913
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 674812653913; DSPS: 22203594; Offset : -2796186678
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 694815053646; DSPS: 22859032; Offset : -2796167317
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 714816870825; DSPS: 23514452; Offset : -2796181037
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 734817990037; DSPS: 24169849; Offset : -2796190974
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 754819578310; DSPS: 24825261; Offset : -2796189590
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 774821328251; DSPS: 25480678; Offset : -2796179098
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 794823028556; DSPS: 26136094; Offset : -2796188195
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 814824524641; DSPS: 26791503; Offset : -2796187132
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=424594530, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{31f5bfa8 type 2 when 827232 android} when 827232
D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=424594530 [*alarm*], flags=0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 834826537967; DSPS: 27446929; Offset : -2796188305
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 854827662490; DSPS: 28102326; Offset : -2796192516
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 874829062535; DSPS: 28757731; Offset : -2796165657
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 894832048778; DSPS: 29413189; Offset : -2796170501
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 914833886113; DSPS: 30068609; Offset : -2796164170
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 934836430896; DSPS: 30724053; Offset : -2796182863
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=424594530, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{9f7fac1 type 2 when 952955 com.android.bluetooth} when 952955
I/ActivityManager(  853): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7979 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,W/bt-smp  ( 1963): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1963): Plain text(LSB ~ MSB) = 6b 86 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 1963): Encrypted text(LSB ~ MSB) = b5 3a d2 0e 85 de 8c da c4 5f 20 d2 7c a6 d9 cf 
W/bt-btm  ( 1963): Stopping oneshot timer
,I/DigitalAppWidgetProvider( 7979): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7979): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@23a2da31
D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=424594530 [*alarm*], flags=0x0
I/ActivityManager(  853): Killing 7310:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10061/pid_7310/cgroup.procs: No such file or directory
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 954837417088; DSPS: 31379445; Offset : -2796173286
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 974839053382; DSPS: 32034859; Offset : -2796184940
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 994840873271; DSPS: 32690278; Offset : -2796165563
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1014841902274; DSPS: 33345672; Offset : -2796173949
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=424594530, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{3f42c266 type 2 when 1017884 com.google.android.gms} when 1017884
D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=424594530 [*alarm*], flags=0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1034843784037; DSPS: 34001094; Offset : -2796184225
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1054845426581; DSPS: 34656508; Offset : -2796189603
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1074847055428; DSPS: 35311921; Offset : -2796178579
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1094848949378; DSPS: 35967343; Offset : -2796176458
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1114851206975; DSPS: 36622777; Offset : -2796177187
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1134852749310; DSPS: 37278188; Offset : -2796191302
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1154854039616; DSPS: 37933590; Offset : -2796182473
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1174854771952; DSPS: 38588974; Offset : -2796182663
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1194856260849; DSPS: 39244383; Offset : -2796189362
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1214858518446; DSPS: 39899817; Offset : -2796189832
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  853): User[0] Flushing usage stats to disk
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1234859440836; DSPS: 40555207; Offset : -2796182761
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1254861993536; DSPS: 41210651; Offset : -2796195803
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
,I/[SystemUI]Clock( 1371): called onTimeUpdated()
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1274863494258; DSPS: 41866060; Offset : -2796188332
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1294864607478; DSPS: 42521456; Offset : -2796173823
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1314866529972; DSPS: 43176879; Offset : -2796174145
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1334868404443; DSPS: 43832301; Offset : -2796191608
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1354869520372; DSPS: 44487697; Offset : -2796174207
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1374871067293; DSPS: 45143108; Offset : -2796183709
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1394873404159; DSPS: 45798545; Offset : -2796196982
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1414874494726; DSPS: 46453940; Offset : -2796174480
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1434877019457; DSPS: 47109383; Offset : -2796182682
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1454879025335; DSPS: 47764809; Offset : -2796191016
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1474882003452; DSPS: 48420266; Offset : -2796173052
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1494884271570; DSPS: 49075700; Offset : -2796163078
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1514885525260; DSPS: 49731102; Offset : -2796191075
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1534886640565; DSPS: 50386498; Offset : -2796174428
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1554889155192; DSPS: 51041941; Offset : -2796192916
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  853): battery changed pluggedType: 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1574891322165; DSPS: 51697372; Offset : -2796192457
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1594892956427; DSPS: 52352785; Offset : -2796175704
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1614894864752; DSPS: 53008208; Offset : -2796189883
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1634896782713; DSPS: 53663630; Offset : -2796164194
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1654898693175; DSPS: 54319053; Offset : -2796176444
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1674901107802; DSPS: 54974492; Offset : -2796172705
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1694902612847; DSPS: 55629901; Offset : -2796162918
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1714904627684; DSPS: 56285328; Offset : -2796192836
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1734907018614; DSPS: 56940766; Offset : -2796182121
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1754908924178; DSPS: 57596188; Offset : -2796168439
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1774911785212; DSPS: 58251642; Offset : -2796176448
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1794914186403; DSPS: 58907081; Offset : -2796186171
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1963): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1814915826760; DSPS: 59562495; Offset : -2796193737
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1834916562324; DSPS: 60217879; Offset : -2796190336
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=424594530, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{3fbb2e54 type 2 when 1853177 com.android.bluetooth} when 1853177
,W/bt-smp  ( 1963): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1963): Plain text(LSB ~ MSB) = 0a 5a 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1963): Encrypted text(LSB ~ MSB) = 85 c0 ac 90 8d 43 56 c0 e9 c4 48 d7 ab 9b 3c 83 
W/bt-btm  ( 1963): Stopping oneshot timer
I/ProcessStatsService(  853): Prepared write state in 16ms
,I/ProcessStatsService(  853): Prepared write state in 16ms
,I/DigitalAppWidgetProvider( 7979): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7979): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@23a2da31
,D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=424594530 [*alarm*], flags=0x0
I/ProcessStatsService(  853): Pruning old procstats: /data/system/procstats/state-2015-12-20-04-11-07.bin
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1854917936276; DSPS: 60873284; Offset : -2796190195
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,V/AlarmManager(  853): RTC_WAKEUP set : Alarm{13c881fd type 0 when 1450659056334 com.google.android.gms} when 1450659056334
,D/LocationManagerService(  853): getAllProviders()=[passive, gps, network]
,I/EventLogService( 4265): Aggregate from 1450657973622 (log), 1450657256217 (data)
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1874919573455; DSPS: 61528697; Offset : -2796170394
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1894921059124; DSPS: 62184106; Offset : -2796179932
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8168): 
D/AndroidRuntime( 8168): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8168): CheckJNI is OFF
D/AndroidRuntime( 8168): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  853): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  853): Killing 6435:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  853): WIN DEATH: Window{1ce1cbd0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  853): Focus left window: Window{1ce1cbd0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  853): Window went away: Window{1ce1cbd0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  853): Skipping PackageSetting{897cdb8 com.example.hello/10317} due to missing metadata
I/ActivityManager(  853):   Force finishing activity ActivityRecord{15ce6e6 u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  853): Display changed displayId=0
D/DSDPConnection( 1747): Display #0 changed.
W/ActivityManager(  853): Spurious death for ProcessRecord{6a2e46d 6435:com.test.thalitest/u0a316}, curProc for 6435: null
I/ActivityManager(  853): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/[LGHome]EVENT( 1874): [Launcher.java:5203:onStart()]onStart
I/[LGHome]EVENT( 1874): [Launcher.java:776:onResume()]onResume
I/art     ( 1937): Explicit concurrent mark sweep GC freed 9944(670KB) AllocSpace objects, 4(96KB) LOS objects, 40% free, 12MB/20MB, paused 1.410ms total 79.849ms
W/System.err( 3648): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1729): Ignoring removeGeofence because network location is disabled.
I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3648): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3648): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3648): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3648): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3648): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3648): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3648): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3648): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3648): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3648): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3648): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 4265): Explicit concurrent mark sweep GC freed 2291(143KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/18MB, paused 6.486ms total 112.716ms
I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8200 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1874): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1874): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1874): [Launcher.java:929:onResume()]onResume end
I/Activity( 1874): Activity.onPostResume() called 
I/art     (  853): Explicit concurrent mark sweep GC freed 76811(4MB) AllocSpace objects, 17(439KB) LOS objects, 33% free, 23MB/35MB, paused 13.931ms total 208.511ms
I/art     (  853): WaitForGcToComplete blocked for 158.659ms for cause Explicit
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
W/[LGHome]LGWallpaperInfo( 1874): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1874): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ResourcesManager( 8200): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17b2465c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17b2465c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  853): Focus entered window: Window{250e8d18 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourcesManager( 1371): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1371): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1874): [setNavigationBarColor] color=0x 0
W/ResourcesManager( 1371): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourcesManager( 1371): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1371): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1371): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): handleShortcutListChanged...
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): handleShortcutListChanged...
D/administrator(  853): Handling package changes for user 0
I/art     (  853): Explicit concurrent mark sweep GC freed 7290(451KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.751ms total 272.957ms
W/InputMethodManagerService(  853): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  853): Got RemoteException sending setActive(false) notification to pid 6435 uid 10316
I/LGEmail ( 8200): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 8200): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{33665d09 u0 com.lge.launcher2/.Launcher t219} time:1909309
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/AndroidRuntime( 8168): Shutting down VM
W/IInputConnectionWrapper( 1874): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1569): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1874): getTextAfterCursor on inactive InputConnection
D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
I/NotificationService(  853): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
D/JobSchedulerService(  853): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  853): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/PackageChangeReceiver( 8200): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/ResourceType(  853): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/AppUp4:PreloadHelper( 7634): added Exclude : com.test.thalitest
E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/ActivityManager(  853): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8229 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  853): Killing 7657:com.android.gallery3d/u0a23 (adj 15): empty #11
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created

```
