#### Test 52383621d5a0cb8_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  853): Killing 5674:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10061/pid_5674/cgroup.procs: No such file or directory
,--------- beginning of main
I/ThermalEngine(  298): Sensor:pa_therm0:32000 mC
D/AndroidRuntime( 6027): 
D/AndroidRuntime( 6027): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6027): CheckJNI is OFF
D/AlertService( 5937): Beginning updateAlertNotification
D/AlertService( 5937): No fired or scheduled alerts
I/NotificationManager( 5937): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5937): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5937): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5937): No events found starting within 1 week.
D/AndroidRuntime( 6027): Calling main entry com.android.commands.am.Am
I/ActivityManager(  853): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{2b481ad #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{2b481ad #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  853): AppWindowTokenEx init.. 
D/ContextHelper(  853): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  853): Focus left window: Window{2d4ce7ca u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/ActivityManager(  853): Killing 5874:com.android.gallery3d/u0a23 (adj 15): empty #11
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/AndroidRuntime( 6027): Shutting down VM
W/libprocessgroup(  853): failed to open /acct/uid_10023/pid_5874/cgroup.procs: No such file or directory
D/SplitWindow(  853): check instance of lgWin Window{36f08cf u0 Starting com.test.thalitest}
I/ActivityManager(  853): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6052 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1941): Closing mic
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 94648296218; DSPS: 3192914; Offset : -2801655363
I/MicrophoneInputStream( 1941): mic_close com.google.android.apps.gsa.speech.audio.u@275c0714
V/AudioRecord( 1941): stop()
D/AudioRecord( 1941): AudioRecord->stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
I/WindowStateAnimator(  853): Starting window displayed
V/AudioFlinger(  281): Record stopped OK
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
V/AudioPolicyManager(  281): stopInput() input 17
V/AudioPolicyService(  281): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  281): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  281): ThreadBase::setParameters() routing=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb435a000
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@28cddb88,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/audio_hw_primary(  281): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
D/PhoneStatusBar( 1378): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1378): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1378):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1378): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1378): draw background and invalidate : color = e000000
D/BarTransitions( 1378): draw background and invalidate : color = f0e0e0e
V/audio_hw_primary(  281): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  281): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  281): disable_audio_route: exit
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
,D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb435a000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
,V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 17
V/AudioPolicyManager(  281): closeInput(17)
V/AudioFlinger(  281): closeInput() 17
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): ThreadBase::exit
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem(  853): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread 0xb435a000 exiting
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  281): removeClient_l() pid 1941, calling pid 281
V/AudioSystem( 1744): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1941): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2755): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3161): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioSystem( 1981): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1378): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): releasing 16 from 1941 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
I/HotwordRecognitionRnr( 1941): Stopping hotword detection.
I/HotwordRecognitionRnr( 1941): Hotword detection finished
D/ContextHelper( 6052): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6052): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6052): Time to load native libraries: 3 ms (timestamps 4928-4931)
,I/LibraryLoader( 6052): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6052): Binding Chromium to main looper Looper (main, tid 1) {c20d2fc}
,I/LibraryLoader( 6052): Expected native library version number "",actual native library version number ""
I/chromium( 6052): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6052): Initializing chromium process, singleProcess=true
,W/art     ( 6052): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6052): ApplicationContext is null in ApplicationStatus
W/chromium( 6052): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6052): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6052): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6052): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6052): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6052): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6052): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6052): Remote Branch: 
I/Adreno-EGL( 6052): Local Patches: 
I/Adreno-EGL( 6052): Reconstruct Branch: 
,V/AudioPolicyService(  281): registerClient() client 0xb551cd20, uid 10316
,D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@157ab119:true
,D/BluetoothAdapterService(656810728)( 1981): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e74557e
W/art     ( 6052): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6052): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6052): CordovaWebView is running on device made by: LGE
,W/art     ( 6052): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6052): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 6052): Activity.onPostResume() called 
,D/OpenGLRenderer( 6052): Render dirty regions requested: true
I/OpenGLRenderer( 6052): Initialized EGL, version 1.4
D/OpenGLRenderer( 6052): Enabling debug mode 0
,D/Atlas   ( 6052): Validating map...
,D/SplitWindow(  853): check instance of lgWin Window{2d7d1289 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6052): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  853): Focus entered window: Window{2d7d1289 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  853): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  853): Displayed com.test.thalitest/.MainActivity: +1s134ms
I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{1f2c1ce2 u0 com.test.thalitest/.MainActivity t220} time:95655
I/Timeline( 6052): Timeline: Activity_idle id: android.os.BinderProxy@15ac65fb time:95682
,W/BindingManager( 6052): Cannot call determinedVisibility() - never saw a connection for the pid: 6052
,D/JsMessageQueue( 6052): Set native->JS mode to OnlineEventsBridgeMode
,D/Finsky  ( 5628): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  853): RTC_WAKEUP set : Alarm{1aceb2cb type 0 when 1449056449444 com.android.vending} when 1449056449444
V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  853): android: cancelAsUser(2) by android
,D/libc-netbsd( 5628): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5628): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5628): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5628): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5628): propertyValue:false
,D/libc-netbsd( 5628): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5628): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/jxcore_app_log( 6052): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622778880
D/JX-Cordova( 6052): jxcore cordova android initializing
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd( 5628): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5628): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 6052): CheckpointMarkThreadRoots callback created = 0x9ad6d4d0
,I/art     ( 6052): CheckpointMarkThreadRoots callback created = 0x9ad6d4a0
,W/SQLiteConnectionPool( 4125): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  853): android: cancelAsUser(2) by android
,I/qtaguid ( 5628): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5628): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5628): untagSocket(41) failed with errno -22
D/Finsky  ( 5628): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430000] >= Server Version [-1]
,I/ActivityManager(  853): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6136 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  853): android: cancelAsUser(2) by android
,W/ResourcesManager( 6136): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6136): VM with version 2.1.0 has multidex support
I/MultiDex( 6136): install
I/MultiDex( 6136): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6136): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/qtaguid ( 5628): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5628): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5628): untagSocket(41) failed with errno -22
W/ActivityThread( 6136): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6136): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a1c6ade: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6136): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  853): Process com.android.contacts (pid 5427) has died
,I/NotificationManager( 6136): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6136): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1733): callingUid 10006, callindPid: 1733
,E/MDM     ( 1733): [80] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/GCM     ( 2016): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2016): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4125): Restart initialization of location
V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 2016): com.google.android.gms: cancel(0) by com.google.android.gms
V/GmsCoreStatsServiceLauncher( 4125): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 2016): location=null
,D/NativeLibraryUtils( 6136): Install completed successfully. count=13 extracted=0
,I/art     ( 5628): CheckpointMarkThreadRoots callback created = 0xb0582490
I/art     ( 5628): CheckpointMarkThreadRoots callback created = 0xb0582450
,I/art     ( 6136): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 6136): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/NotificationManager( 6136): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 5628): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5628): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  853): android: cancelAsUser(2) by android
,I/ThermalEngine(  298): Sensor:pa_therm0:32000 mC
,I/qtaguid ( 5628): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5628): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5628): untagSocket(41) failed with errno -22
W/jxcore-log( 6052): Initializing JXcore engine
W/jxcore-log( 6052): JXcore engine is ready
W/jxcore-log( 6052): Starting JXcore engine
,W/.test.thalitest( 6052): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6310]" dev="sockfs" ino=6310 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6052): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6052): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6106]" dev="sockfs" ino=6106 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6052): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6052): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6052): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[28455]" dev="sockfs" ino=28455 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/ResourcesManager( 5628): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5628): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5628): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5628): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 5628): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{34ff72bd type 0 when 1449056452115 com.android.vending} when 1449056452115
,D/DeviceConnectionService( 1733): client connected with version: 8296000
,D/Finsky  ( 5628): [674] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,W/jxcore-log( 6052): Platform android
W/jxcore-log( 6052): 
W/jxcore-log( 6052): Process ARCH arm
W/jxcore-log( 6052): 
V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  853): android: cancelAsUser(2) by android
,D/libc-netbsd( 5628): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5628): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5628): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5628): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 5628): propertyValue:false
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{37bc2af1 type 0 when 1449056452834 com.google.android.googlequicksearchbox} when 1449056452834
,I/jxcore-log( 6052): JXcore Cordova bridge is ready!
I/jxcore-log( 6052): 
,W/jxcore-log( 6052): JXcore engine is started
I/chromium( 6052): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 6052): Skipped 211 frames!  The application may be doing too much work on its main thread.
,E/jxcore  ( 6052): Error!: Cannot find module '../server-address.js'
E/jxcore  ( 6052): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium( 6052): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
,D/InputDispatcher(  853): Focus left window: Window{2d7d1289 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (2337 us)
,W/PluginManager( 6052): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 39ms. Plugin should use CordovaInterface.getThreadPool().
I/[LGHome]EVENT( 1879): [Launcher.java:5203:onStart()]onStart
,I/[LGHome]EVENT( 1879): [Launcher.java:776:onResume()]onResume
,I/[LGHome]LGActivityUtil( 1879): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1879): [Launcher.java:929:onResume()]onResume end
I/Activity( 1879): Activity.onPostResume() called 
D/WeatherAncestor( 2733): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:40:53
D/UpdateThreadPoolManager( 2733): 2 : This is isUpdating : false
,W/[LGHome]LGWallpaperInfo( 1879): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1879): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/WeatherService( 2733): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2733): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 2733): 2 : shouldTimeTickRegistered().........
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/PhoneStatusBar( 1378): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@28cddb88,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WeatherAncestor( 2733): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:40:53
D/InputDispatcher(  853): Focus entered window: Window{2d4ce7ca u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/WeatherService( 2733): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2733): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2733): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2733): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2733): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 2733): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2733): 2 : This is isUpdating : false
D/WeatherService( 2733): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2733): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2733): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2733): 2 : Fixed theme : optimus
D/WeatherReflect( 2733): 2 : Map key string is -2
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1879): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  853): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/IInputConnectionWrapper( 6052): showStatusIcon on inactive InputConnection
,D/lim     ( 2733): 2 : time = 12:40
I/WeatherReflect( 2733): Model Name : LG-D722
D/WeatherTheme( 2733): 2 : exactly same view!
D/WeatherTheme( 2733): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2733): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2733): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2733): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@28cddb88,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1378): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/Timeline( 1879): Timeline: Activity_idle id: android.os.BinderProxy@7ad924a time:100463
I/[SystemUI]NavigationThemeResource( 1378): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1378):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1378): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/HotwordRecognitionRnr( 1941): Starting hotword detection.
D/BarTransitions( 1378): draw background and invalidate : color = f4000000
D/BarTransitions( 1378): draw background and invalidate : color = f4ebebeb
I/MicrophoneInputStream( 1941): mic_starting com.google.android.apps.gsa.speech.audio.u@2fd1f5e8
V/AudioRecord( 1941): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
,V/AudioRecord( 1941): set(): mSessionId 23
V/AudioPolicyManager(  281): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 23, flags 0
V/AudioPolicyManager(  281): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  281): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  281): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb4036520)
V/audio_hw_primary(  281): adev_open_input_stream: exit
V/AudioFlinger(  281): openInput_l() openInputStream returned input 0xb4036520, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  281): openInput_l() created record thread: ID 24 thread 0xb3851000
V/AudioSystem(  281): ioConfigChanged() event 3, ioHandle 24
,V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioSystem( 1981): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
I/AudioFlinger(  281): AudioFlinger's thread 0xb3851000 ready to run
D/audio_hw_primary(  281): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioSystem( 3161): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1744): ioConfigChanged() event 3, ioHandle 24
D/audio_hw_primary(  281): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioSystem(  853): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1941): ioConfigChanged() event 3, ioHandle 24
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioSystem( 2755): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1378): ioConfigChanged() event 3, ioHandle 24
V/AudioFlinger(  281): openRecord() lSessionId: 23 input 24
V/AudioFlinger(  281): getOrphanEffectChain_l session 23 index -2
V/AudioFlinger(  281): acquiring 23 from 1941, for -1
V/AudioFlinger(  281):  added new entry for 23
V/AudioRecord( 1941): start, sync event 0 trigger session 0
V/AudioRecord( 1941): mAudioRecord->start()
V/AudioFlinger(  281): RecordHandle::start()
V/AudioFlinger(  281): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  281): startInput() module primary->input primary(24)
V/AudioPolicyManager(  281): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  281): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  281): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  281): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  281): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  281): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  281): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  281): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  281): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3851000
V/AudioFlinger::PatchPanel(  281): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  281): createAudioPatch() added new patch handle 25 halHandle 0
,V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): setInputDevice() createAudioPatch returned 0 patchHandle 25
V/AudioPolicyManager(  281): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  281): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  281): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyService(  281): AudioCommandThread() adding set parameter string hotword_active=1, io 24 ,delay 0
V/AudioPolicyService(  281): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing set parameters string hotword_active=1, io 24
V/AudioFlinger(  281): setParameters(): io 24, keyvalue hotword_active=1, calling pid 281
V/AudioFlinger(  281): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3851000
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1941): mic_started com.google.android.apps.gsa.speech.audio.u@2fd1f5e8
V/msm8974_platform(  281): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  281): start_input_stream: enter: stream(0xb4036520)usecase(7: audio-record)
V/voice   (  281): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  281): start_input_stream: usecase(7)
E/audio_hw_primary(  281): select_devices: enter and usecase(7)
V/msm8974_platform(  281): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  281): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  281): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
,V/audio_hw_lge_primary(  281): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  281): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  281): enable_snd_device: enter  144
D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  281): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  281): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  281): ACDB -> send_adm_topology
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  281): ACDB -> send_asm_topology
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  281): ACDB -> send_audtable
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  281): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  281): ACDB -> send_audvoltable
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  281): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  281): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  281): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  281): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  281): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  281): enable_audio_route: exit
D/audio_hw_primary(  281): select_devices: done
V/audio_hw_primary(  281): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  281): start_input_stream: exit
,I/HotwordWorker( 1941): onReady
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{163fa1 u0 com.lge.launcher2/.Launcher t219} time:100719
,D/InputDispatcher(  853): Window went away: Window{2d7d1289 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,W/OpenGLRenderer( 1879): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 1879): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1879): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1879): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1879): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1879): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,I/ActivityManager(  853): Killing 5446:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10069/pid_5446/cgroup.procs: No such file or directory
,I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  271): 
I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  298): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
,I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
,I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=415693486, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,D/WeatherService( 2733): 2 : TimeTick Intent has been received, Time(hour:min:sec) 12:41:0
D/WeatherService( 2733): 2 : TimeTick Intent And Screen On
D/WeatherService( 2733): 2 : SDK version : 21
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2733): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2733): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2733): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2733): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2733): 2 : This is isUpdating : false
D/WeatherService( 2733): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2733): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2733): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2733): 2 : Fixed theme : optimus
D/WeatherReflect( 2733): 2 : Map key string is -2
D/lim     ( 2733): 2 : time = 12:41
I/WeatherReflect( 2733): Model Name : LG-D722
D/WeatherTheme( 2733): 2 : Different view - status_min_formatted : 40 != 41
D/WeatherTheme( 2733): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2733): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2733): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2733): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2733): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2733): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2733): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2733): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2733): forecast size is 0
,D/Theme   ( 2733): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2733): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2733): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2733): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2733): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2733): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2733): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2733): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2733): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2733): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2733): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2733): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2733): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2733): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2733): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2733): url is : null
D/Theme   ( 2733): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2733): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2733): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2733): 2 : update view, appWidgetId: 2
D/WeatherService( 2733): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 12:41:0
,D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=415693486 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  298): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  298): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{2e6193dc type 0 when 1449056466428 com.android.vending} when 1449056466428
,W/ContextImpl( 3626): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 5628): [665] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5628): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 114651057410; DSPS: 3848364; Offset : -2801639008
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/MusicWidget( 2645): mDelayedStopHandler : unbind
,I/MusicBrowser( 2755): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2755): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2755): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2755): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2755): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2755): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2755): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2755): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  853):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@177c4b8acom.lge.music.MediaPlaybackService$6@15ac65fb
,D/MusicBrowser( 2755): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2755): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2755): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2755): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2755): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@314fbd01
I/MusicBrowser( 2755): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2755): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2755): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2755): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2755): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2755): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2755): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2755): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2755): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2755): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2755): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2755): [MediaPlaybackService.java:6745:release()] oooooo 
,I/MusicBrowser( 2755): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2755): reset
V/MediaPlayer[Native]( 2755): setListener
V/MediaPlayer[Native]( 2755): disconnect
V/MediaPlayer[Native]( 2755): destructor
,V/AudioFlinger(  281): releasing 19 from 2755 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/MediaPlayer[Native]( 2755): disconnect
D/MusicBrowser( 2755): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2755): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2755): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2755): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2755): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2755): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2755): [SmartShareManagerClient] unregisterListener: 479991320
W/SmartShareClient( 2755): [SmartShareManagerClient] unregisterListener invalid listener: 479991320
I/SmartShareClient( 2755): [SmartShareManagerClient] terminate service: 2755/MediaPlaybackService/657733615
E/HomeCloudIF( 2755): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2755): [SmartShareManagerClient] unbindService context:android.app.Application@2bc0e871
V/CloudHub( 2755): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2755): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2755): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2755): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2755): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  853): Killing 5897:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/CloudHub( 2755): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29987
,W/libprocessgroup(  853): failed to open /acct/uid_10086/pid_5897/cgroup.procs: No such file or directory
,I/GCM     ( 2016): GCM message com.google.android.gms 0:1449056471064769%136ddda6f9fd7ecd
I/GCM     ( 4125): Message from 745476177629 null
,I/GCoreUlr( 1733): GCM message received Intent { act=com.google.android.c2dm.intent.RECEIVE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.location.reporting.service.GcmBroadcastReceiver (has extras) }
,I/GCoreUlr( 1733): Received GCM notification for account#2# timestamp:1449056471057
,I/GCoreUlr( 1733): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_INSISTENT_SYNC cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{account=Account {name=thalitester@gmail.com, type=com.google}, label=GcmBroadcastReceiver}]
I/GCoreUlr( 1733): DispatchingService.onCreate()
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 16742(910KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 11MB/18MB, paused 1.480ms total 70.026ms
,E/DataBuffer( 1733): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@e0dbc5b)
W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     (  853): Explicit concurrent mark sweep GC freed 29849(1371KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 2.614ms total 150.128ms
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/GCoreUlr( 1733): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/art     ( 2016): Explicit concurrent mark sweep GC freed 12358(742KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/19MB, paused 1.625ms total 53.624ms
,I/GCoreUlr( 1733): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1733): Unbound from all location providers
I/GCoreUlr( 1733): DispatchingService.onDestroy()
I/GCoreUlr( 1733): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1733): Stopping handler for UlrDispSvcSlow
,I/GCoreUlr( 1733): Unbound from all location providers
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/charger_monitor(  477): init target 500000
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  853): battery changed pluggedType: 2
I/CloudHub( 2755): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19947
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 134652095473; DSPS: 4503758; Offset : -2801640418
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{33b01955 type 2 when 139285 com.google.android.gms} when 139285
,V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2016): Vacuum at: now=1449056492637 tag=VacuumService
D/UdcCache:FPQuery( 4125): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/GetConfigurationSnapshotOperation( 2016): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2016): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2016): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 2016): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/libc-netbsd( 2016): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2016): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2016): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2016): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 2016): propertyValue:false
D/libc-netbsd( 2016): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2016): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2016): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 2016): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Uploader( 2016):  no longer exists, so no auth token.
D/GetCommittedConfigurationOperation( 2016): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2016): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/GetCommittedConfigurationOperation( 2016): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2016): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2016): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2016): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2016): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/CloudHub( 2755): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2755): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28065 ms ago)
,D/qdlights(  853): set_light_backlight: 251
,D/qdlights(  853): set_light_backlight: 248
,D/qdlights(  853): set_light_backlight: 245
,D/qdlights(  853): set_light_backlight: 241
,D/qdlights(  853): set_light_backlight: 238
,D/qdlights(  853): set_light_backlight: 235
,D/qdlights(  853): set_light_backlight: 231
,D/qdlights(  853): set_light_backlight: 228
,D/qdlights(  853): set_light_backlight: 225
,D/qdlights(  853): set_light_backlight: 221
,D/qdlights(  853): set_light_backlight: 218
,D/qdlights(  853): set_light_backlight: 215
,D/qdlights(  853): set_light_backlight: 211
,D/qdlights(  853): set_light_backlight: 208
,D/qdlights(  853): set_light_backlight: 205
,D/qdlights(  853): set_light_backlight: 201
,D/qdlights(  853): set_light_backlight: 198
,D/qdlights(  853): set_light_backlight: 195
,D/qdlights(  853): set_light_backlight: 191
,D/qdlights(  853): set_light_backlight: 188
,D/qdlights(  853): set_light_backlight: 185
,D/qdlights(  853): set_light_backlight: 181
,D/qdlights(  853): set_light_backlight: 178
,D/qdlights(  853): set_light_backlight: 175
,D/qdlights(  853): set_light_backlight: 171
,D/qdlights(  853): set_light_backlight: 168
,D/qdlights(  853): set_light_backlight: 165
,D/qdlights(  853): set_light_backlight: 161
,D/qdlights(  853): set_light_backlight: 158
,D/qdlights(  853): set_light_backlight: 155
,D/qdlights(  853): set_light_backlight: 151
,D/qdlights(  853): set_light_backlight: 148
,D/qdlights(  853): set_light_backlight: 145
,D/qdlights(  853): set_light_backlight: 141
,D/qdlights(  853): set_light_backlight: 138
,D/qdlights(  853): set_light_backlight: 135
,D/qdlights(  853): set_light_backlight: 131
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
D/qdlights(  853): set_light_backlight: 128
,D/qdlights(  853): set_light_backlight: 125
,D/qdlights(  853): set_light_backlight: 121
,D/qdlights(  853): set_light_backlight: 118
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdlights(  853): set_light_backlight: 115
D/qdlights(  853): set_light_backlight: 111
,D/qdlights(  853): set_light_backlight: 108
,D/qdlights(  853): set_light_backlight: 105
,D/qdlights(  853): set_light_backlight: 102
,D/qdlights(  853): set_light_backlight: 99
,D/qdlights(  853): set_light_backlight: 96
,D/qdlights(  853): set_light_backlight: 92
,D/qdlights(  853): set_light_backlight: 89
,D/qdlights(  853): set_light_backlight: 86
,D/qdlights(  853): set_light_backlight: 82
,D/qdlights(  853): set_light_backlight: 79
,D/qdlights(  853): set_light_backlight: 76
,D/qdlights(  853): set_light_backlight: 72
,D/qdlights(  853): set_light_backlight: 69
,D/qdlights(  853): set_light_backlight: 66
,D/qdlights(  853): set_light_backlight: 62
,D/qdlights(  853): set_light_backlight: 59
,D/qdlights(  853): set_light_backlight: 56
,D/qdlights(  853): set_light_backlight: 52
,D/qdlights(  853): set_light_backlight: 49
,D/qdlights(  853): set_light_backlight: 46
,D/qdlights(  853): set_light_backlight: 42
,D/qdlights(  853): set_light_backlight: 39
,D/qdlights(  853): set_light_backlight: 36
,D/qdlights(  853): set_light_backlight: 32
,D/qdlights(  853): set_light_backlight: 29
,D/qdlights(  853): set_light_backlight: 26
,D/qdlights(  853): set_light_backlight: 22
,D/qdlights(  853): set_light_backlight: 19
,D/qdlights(  853): set_light_backlight: 16
,D/qdlights(  853): set_light_backlight: 12
,D/qdlights(  853): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 154653923124; DSPS: 5159179; Offset : -2801674365
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35057 ms ago)
I/PowerManagerService(  853): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  853): ALS enabled for SRE
,D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35078 ms ago)
W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  853): Sleeping (uid 1000)...
D/LPWGController(  853): [updateScreenState] screen on = false
D/LPWGController(  853): disable proximity sensor
,D/LPWGController(  853): enable proximity sensor
I/SensorManager(  853): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@12ded758] by com.android.server.power.ProximitySensorListener.enable():120
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
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35145 ms ago)
I/Adreno-EGL(  853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  853): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  853): Build Date: 03/02/15 Mon
I/Adreno-EGL(  853): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  853): Remote Branch: 
I/Adreno-EGL(  853): Local Patches: 
I/Adreno-EGL(  853): Reconstruct Branch: 
,I/Sensors (  414): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
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
,D/qdlights(  853): set_light_backlight: 0
,I/SensorManager(  853): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  853): activate: handle is 46, disable
V/sensors_hal_Ctx(  853): activate sensors is 1000000000000
D/sensors_hal_LP2(  853): enable: handle=46
D/sensors_hal_LP2(  853): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  853): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  853): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  853): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,V/ActivityManager(  853): Display changed displayId=0
,I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1378): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/DSDPConnection( 1744): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  853): Excessive delay in setPowerMode(): 210ms
I/QCOM PowerHAL(  853): Got set_interactive hint
,I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/KeyguardViewMediator( 1378): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1378): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
,I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
D/KeyguardViewMediator( 1378): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1378): handleNotifyScreenOff
I/HotwordDetector( 1941): Closing mic
I/MicrophoneInputStream( 1941): mic_close com.google.android.apps.gsa.speech.audio.u@2fd1f5e8
V/AudioRecord( 1941): stop()
D/AudioRecord( 1941): AudioRecord->stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioFlinger(  281): Record stopped OK
V/AudioPolicyManager(  281): stopInput() input 24
V/AudioPolicyService(  281): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  281): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch handle 25
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  281): ThreadBase::setParameters() routing=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
,V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3851000
D/audio_hw_primary(  281): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
D/ScreenTurnOffBySensor( 1378): unregisterProximitySensor
D/WifiServerServiceExt(  853): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=on, calling pid 853
D/StatusBarWindowView( 1378): onScreenTurnedOff why = 3
I/WifiServerServiceExt(  853): set CMD_KT_SCAN_INTERVAL
,V/audio_hw_primary(  281): stop_input_stream: enter: usecase(7: audio-record)
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
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: enter: screen_state=on
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: exit
V/voice   (  281): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  281): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  281): platform_set_parameters: exit with code(0)
V/AudioPolicyManager(  281): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  281): removeAudioPatch() handle 20 af handle 25
V/AudioPolicyService(  281): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  281): inserting command: 10 at index 0, num commands 0
,V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyService(  281): AudioCommandThread() adding set parameter string hotword_active=0, io 24 ,delay 0
V/AudioPolicyService(  281): inserting command: 3 at index 0, num commands 0
V/lge_audio_loopback(  281): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  281): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  281): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  281): adev_set_parameters: exit with code(0)
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing set parameters string hotword_active=0, io 24
V/AudioFlinger(  281): setParameters(): io 24, keyvalue hotword_active=0, calling pid 281
V/AudioFlinger(  281): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3851000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 24
V/AudioFlinger(  281): releasing 23 from 1941 for -1
V/AudioPolicyManager(  281): closeInput(24)
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/AudioFlinger(  281): closeInput() 24
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 24
,V/AudioSystem( 1941): ioConfigChanged() event 4, ioHandle 24
V/AudioFlinger(  281): ThreadBase::exit
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioFlinger(  281): RecordThread 0xb3851000 exiting
V/AudioSystem(  853): ioConfigChanged() event 4, ioHandle 24
V/AudioSystem( 1378): ioConfigChanged() event 4, ioHandle 24
V/AudioSystem( 1744): ioConfigChanged() event 4, ioHandle 24
V/AudioSystem( 1981): ioConfigChanged() event 4, ioHandle 24
V/AudioSystem( 2755): ioConfigChanged() event 4, ioHandle 24
V/AudioSystem( 3161): ioConfigChanged() event 4, ioHandle 24
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  281): removeClient_l() pid 1941, calling pid 281
I/HotwordRecognitionRnr( 1941): Hotword detection finished
I/HotwordRecognitionRnr( 1941): Stopping hotword detection.
,D/GpsLocationProvider(  853): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1841): |CORE| sendScreenState: state:true
I/Sensors (  414): sns_pwr.c(301):releasing wakelock
,I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1805): lockStatus = 0
I/LEDService( 1805): updateLightsLocked : turn off led
,D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1788): action : android.intent.action.SCREEN_ON
D/LEDHandler( 1805): RESTART MSG
D/NfcServiceNXP( 1788): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1788): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1788): isRequireNfcCRouting() return true
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
D/SplitWindow(  853): check instance of lgWin Window{aaf0917 u0 SearchPanel}
,D/InputDispatcher(  853): Window went away: Window{e529e56 u0 SearchPanel}
,I/[SystemUI]Clock( 1378): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1378): time changed, timezoneChanged : false
,D/Ulp_jni (  853): JNI:system_update. Event-0
,V/PhoneApp( 1744): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2733): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:41:50
,D/WeatherService( 2733): 2 : ACTION screen on
D/WeatherService( 2733): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2733): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2733): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:41:50
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): ACTION_SCREEN_ON
D/AppCleanupService( 4060): android.intent.action.SCREEN_ON
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=off, calling pid 853
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=off
V/voice   (  281): voice_set_parameters: enter: screen_state=off
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: exit
V/voice   (  281): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  281): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  281): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  281): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  281): adev_set_parameters: exit with code(0)
D/WifiController(  853): CMD_SCREEN_OFF 
D/WifiController(  853): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  853): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1841): |CORE| sendScreenState: state:false
,I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): updateLightsLocked : turn on led
E/LEDService( 1805): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1805): Can't handle this request of patternId:0
D/LEDHandler( 1805): RESTART MSG
D/VolumeVibrator( 1805): clear
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1788): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1788): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1879): [Launcher.java:1711:onReceive()]Screen Off
W/ActivityManager(  853): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,V/PhoneApp( 1744): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2733): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:41:50
D/WeatherService( 2733): 2 : ACTION screen off
D/WeatherService( 2733): 2 : TimeTick Receiver Unregister
D/WeatherService( 2733): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:41:50
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): ACTION_SCREEN_OFF
D/AppCleanupService( 4060): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4060): AppUsageStatsSaveTask
E/NxpNfcJni( 1788): getReconnectState = 0x0
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
D/LNfcService( 1788): isRequireNfcCRouting() return true
D/LNfcService( 1788): isHCERoutingtoHost() return : true
D/NfcService( 1788): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): newParams.techmask= mTechMask: 0
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): screenState= 1
E/NxpNfcJni( 1788): getReconnectState = 0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{161104 type 2 when 161067 com.android.systemui} when 161067
,D/KeyguardViewMediator( 1378): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1744): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1744): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1744): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1744): getCallState : 0
,D/PhoneUtils( 1744): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1744): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1744): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1378): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1378): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 174656466656; DSPS: 5814622; Offset : -2801663767
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,D/charger_monitor(  477): init target 500000
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
,I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=415693486, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{2faca6ed type 2 when 189074 android} when 189074
V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{2fad7922 type 2 when 187137 com.google.android.gms} when 187137
,D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=415693486 [*alarm*], flags=0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 194659064514; DSPS: 6470067; Offset : -2801658339
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 214660729766; DSPS: 7125481; Offset : -2801640932
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 234663271609; DSPS: 7780925; Offset : -2801662671
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  477): init target 500000
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 254665154229; DSPS: 8436346; Offset : -2801641519
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ClearcutLoggerApiImpl( 2016): disconnect managed GoogleApiClient
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 274667699118; DSPS: 9091790; Offset : -2801660028
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): init target 500000
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 294669342757; DSPS: 9747204; Offset : -2801664469
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 314671883895; DSPS: 10402647; Offset : -2801656264
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=415693486, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{1874040f type 2 when 333844 android} when 333844
D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=415693486 [*alarm*], flags=0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ActivityManager(  853): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6483 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6483): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 334673834981; DSPS: 11058071; Offset : -2801658016
,I/NotificationManager(  853): android: cancelAsUser(-1874035846) by android
V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2016): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  853): Explicit concurrent mark sweep GC freed 46994(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 24MB/36MB, paused 3.297ms total 227.453ms
,W/art     ( 6483): Attempt to remove local handle scope entry from IRT, ignoring
,I/NotificationManager(  853): android: cancelAsUser(-1548111331) by android
,D/libc-netbsd( 6483): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6483): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  277): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  277): App 10086 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/NotificationManager( 6483): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,I/ActivityManager(  853): Killing 5937:com.android.calendar/u0a13 (adj 15): empty #11
,I/NotificationManager(  853): android: cancelAsUser(2145784878) by android
W/libprocessgroup(  853): failed to open /acct/uid_10013/pid_5937/cgroup.procs: No such file or directory
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/LocationManagerService(  853): remove 3e9fdea4
,D/LocationManagerService(  853): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  853): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  853): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  853): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=415693486, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): RTC_WAKEUP set : Alarm{4c74dda type 0 when 1449056699660 com.google.android.gms} when 1449056699660
I/ActivityManager(  853): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6548 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 435us total 47.610ms
,I/EventLogService( 4125): Aggregate from 1449056425258 (log), 1449054899572 (data)
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 401us total 31.275ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 459us total 31.387ms
,I/DigitalAppWidgetProvider( 6548): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6548): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1211cce
I/ActivityManager(  853): Killing 5775:com.google.android.gm/u0a53 (adj 15): empty #11
D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=415693486 [*alarm*], flags=0x0
,W/libprocessgroup(  853): failed to open /acct/uid_10053/pid_5775/cgroup.procs: No such file or directory
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 354675496744; DSPS: 11713485; Offset : -2801643733
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{132773e7 type 2 when 364257 android} when 364257
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 374678747257; DSPS: 12368952; Offset : -2801659226
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 394681747197; DSPS: 13024410; Offset : -2801650035
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 414684360888; DSPS: 13679856; Offset : -2801660907
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 434686907235; DSPS: 14335299; Offset : -2801647441
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 454688745976; DSPS: 14990719; Offset : -2801639808
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 474691736337; DSPS: 15646177; Offset : -2801640169
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 494694154139; DSPS: 16301617; Offset : -2801663773
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 514696702049; DSPS: 16957060; Offset : -2801648796
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 534699239228; DSPS: 17612503; Offset : -2801644576
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 554701787502; DSPS: 18267947; Offset : -2801659831
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 574704344839; DSPS: 18923391; Offset : -2801665970
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 594706888215; DSPS: 19578834; Offset : -2801655502
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 614709432532; DSPS: 20234277; Offset : -2801645706
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 634711975961; DSPS: 20889721; Offset : -2801664138
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 654714519864; DSPS: 21545164; Offset : -2801653376
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 674717066414; DSPS: 22200607; Offset : -2801639708
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 694719611614; DSPS: 22856051; Offset : -2801658062
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 714722157284; DSPS: 23511494; Offset : -2801645273
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 734723798787; DSPS: 24166908; Offset : -2801651486
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 754726342165; DSPS: 24822351; Offset : -2801641274
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 774728888927; DSPS: 25477795; Offset : -2801658041
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 794731884858; DSPS: 26133253; Offset : -2801652780
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 814734298496; DSPS: 26788692; Offset : -2801649850
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 834736843331; DSPS: 27444135; Offset : -2801638234
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  853): tsOffsetIs: Apps: 854739387856; DSPS: 28099579; Offset : -2801657264
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 874741932483; DSPS: 28755022; Offset : -2801645414
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 894744664821; DSPS: 29410472; Offset : -2801659684
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 914747211741; DSPS: 30065915; Offset : -2801645748
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 934749757722; DSPS: 30721359; Offset : -2801662983
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=415693486, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{38c6eb94 type 2 when 952992 com.android.bluetooth} when 952992
D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=415693486 [*alarm*], flags=0x0
,W/bt-smp  ( 1981): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1981): Plain text(LSB ~ MSB) = f8 f2 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1981): Encrypted text(LSB ~ MSB) = a7 40 69 7a e1 36 5b 52 3c d9 d1 80 53 6e 77 dd 
W/bt-btm  ( 1981): Stopping oneshot timer
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 954751328336; DSPS: 31376770; Offset : -2801649366
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 974753881456; DSPS: 32032214; Offset : -2801659331
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 994756133793; DSPS: 32687648; Offset : -2801665321
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1014758549461; DSPS: 33343087; Offset : -2801660567
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=415693486, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{10f1963d type 2 when 1018147 com.google.android.gms} when 1018147
,D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=415693486 [*alarm*], flags=0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1034760954348; DSPS: 33998525; Offset : -2801636026
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1054763510331; DSPS: 34653969; Offset : -2801643623
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1074766048762; DSPS: 35309412; Offset : -2801638046
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1094768591515; DSPS: 35964856; Offset : -2801658849
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1114771121455; DSPS: 36620299; Offset : -2801661790
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1134773663944; DSPS: 37275742; Offset : -2801652234
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1154776067117; DSPS: 37931181; Offset : -2801659897
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1174778613931; DSPS: 38586624; Offset : -2801646094
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1194781148455; DSPS: 39242067; Offset : -2801644581
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1214783693135; DSPS: 39897511; Offset : -2801663299
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  853): User[0] Flushing usage stats to disk
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1234785334322; DSPS: 40552924; Offset : -2801639362
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1254787163276; DSPS: 41208344; Offset : -2801641749
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1274789699987; DSPS: 41863787; Offset : -2801637710
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1294792241282; DSPS: 42519231; Offset : -2801660204
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1314794779293; DSPS: 43174674; Offset : -2801655153
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1334797189027; DSPS: 43830113; Offset : -2801656203
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1354799726935; DSPS: 44485556; Offset : -2801651072
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1374802269273; DSPS: 45140999; Offset : -2801641798
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1394803904108; DSPS: 45796413; Offset : -2801654834
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1414806445975; DSPS: 46451856; Offset : -2801646055
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1434808984875; DSPS: 47107299; Offset : -2801640166
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1454812012210; DSPS: 47762759; Offset : -2801664615
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1474814551213; DSPS: 48418202; Offset : -2801658468
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1494817097507; DSPS: 49073645; Offset : -2801645184
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1514819633490; DSPS: 49729088; Offset : -2801641978
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1534821287963; DSPS: 50384503; Offset : -2801666024
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1554823829255; DSPS: 51039946; Offset : -2801657950
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1574826374873; DSPS: 51695389; Offset : -2801645187
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1594828913301; DSPS: 52350832; Offset : -2801639692
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1614830940691; DSPS: 53006259; Offset : -2801657084
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1634833480059; DSPS: 53661702; Offset : -2801650624
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1654836022394; DSPS: 54317145; Offset : -2801641299
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1674838039366; DSPS: 54972571; Offset : -2801638097
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1694840580401; DSPS: 55628015; Offset : -2801660826
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1714843121329; DSPS: 56283458; Offset : -2801652830
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1734845532260; DSPS: 56938897; Offset : -2801652865
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1754848066940; DSPS: 57594340; Offset : -2801651144
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1774850609171; DSPS: 58249783; Offset : -2801641899
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1794853152028; DSPS: 58905227; Offset : -2801662728
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/HeadsetStateMachine( 1981): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1378): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1378): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1378): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  853): battery changed pluggedType: 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1814855697284; DSPS: 59560670; Offset : -2801650326
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1834858120242; DSPS: 60216109; Offset : -2801638282
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=415693486, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{27ed6783 type 2 when 1853019 com.android.bluetooth} when 1853019
,W/bt-smp  ( 1981): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1981): Plain text(LSB ~ MSB) = 55 99 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1981): Encrypted text(LSB ~ MSB) = 14 c9 0b 8a 50 b2 a8 ec 41 71 60 99 ab 21 92 da 
W/bt-btm  ( 1981): Stopping oneshot timer
I/ProcessStatsService(  853): Prepared write state in 13ms
,I/ProcessStatsService(  853): Prepared write state in 8ms
,I/DigitalAppWidgetProvider( 6548): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6548): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1211cce
D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=415693486 [*alarm*], flags=0x0
,I/ProcessStatsService(  853): Pruning old procstats: /data/system/procstats/state-2015-12-01-12-15-50.bin
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1854859673361; DSPS: 60871520; Offset : -2801641794
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1378): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1378): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1378): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1378): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1874862216789; DSPS: 61526964; Offset : -2801661426
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 1894863861053; DSPS: 62182378; Offset : -2801665085
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 6793): 
D/AndroidRuntime( 6793): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6793): CheckJNI is OFF
D/AndroidRuntime( 6793): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  853): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  853): Killing 6052:com.test.thalitest/u0a316 (adj 15): stop com.test.thalitest
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
W/PackageSettings(  853): Skipping PackageSetting{687152d com.example.hello/10030} due to missing metadata
I/ActivityManager(  853): Killing 5131:com.lge.qremote/u0a106 (adj 15): empty for 1814s
I/ActivityManager(  853): Killing 5708:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty for 1814s
I/ActivityManager(  853): Killing 5974:com.android.providers.calendar/u0a14 (adj 15): empty for 1814s
W/ActivityManager(  853): Spurious death for ProcessRecord{27f12d00 6052:com.test.thalitest/u0a316}, curProc for 6052: null
I/ActivityManager(  853): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/art     ( 1879): Explicit concurrent mark sweep GC freed 7060(408KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.374ms total 45.607ms
W/libprocessgroup(  853): failed to open /acct/uid_10106/pid_5131/cgroup.procs: No such file or directory
I/art     ( 1941): Explicit concurrent mark sweep GC freed 2601(149KB) AllocSpace objects, 3(713KB) LOS objects, 40% free, 12MB/21MB, paused 1.779ms total 63.373ms
E/lowmemorykiller(  243): Error opening /proc/5708/oom_score_adj; errno=2
W/ActivityManager(  853): Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  853): android.os.DeadObjectException
W/ActivityManager(  853): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  853): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  853): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager(  853): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
W/ActivityManager(  853): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  853): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
W/ActivityManager(  853): Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  853): android.os.DeadObjectException
W/ActivityManager(  853): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  853): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  853): 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
W/ActivityManager(  853): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
W/ActivityManager(  853): 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
W/ActivityManager(  853): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
W/ActivityManager(  853): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  853): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_5708/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_10014/pid_5974/cgroup.procs: No such file or directory
D/KeyguardModel( 1378): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/QCNEJ   ( 1841): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/System.err( 3626): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3626): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3626): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3626): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3626): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3626): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3626): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3626): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3626): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3626): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3626): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3626): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6819 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  853): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6833 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1378): onReceive = android.intent.action.PACKAGE_REMOVED
I/art     (  853): Explicit concurrent mark sweep GC freed 38032(2MB) AllocSpace objects, 10(363KB) LOS objects, 33% free, 24MB/36MB, paused 7.309ms total 231.596ms
I/art     (  853): WaitForGcToComplete blocked for 91.343ms for cause Explicit
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1378): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1378): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 6819): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LockScreenSettings( 6833): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1378): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1378): createShortcutInfo...
D/KeyguardModel( 1378): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1378): createShortcutInfo...
W/ResourceType( 1378): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1378): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1378): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1378): createShortcutInfo...
W/ResourceType( 1378): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1378): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1378): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1378): createShortcutInfo...
W/ResourceType( 1378): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1378): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1378): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1378): createShortcutInfo...
I/ActivityManager(  853): Killing 6136:com.google.android.gms:car/u0a6 (adj 15): empty for 1807s
D/administrator(  853): Handling package changes for user 0
D/KeyguardModel( 1378): handleShortcutListChanged...
W/libprocessgroup(  853): failed to open /acct/uid_10006/pid_6136/cgroup.procs: No such file or directory
D/KeyguardModel( 1378): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1378): createShortcutInfo...
I/art     (  853): Explicit concurrent mark sweep GC freed 4552(241KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 4.088ms total 263.938ms
D/KeyguardModel( 1378): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1378): createShortcutInfo...
W/ResourceType( 1378): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1378): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1378): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1378): createShortcutInfo...
W/ResourceType( 1378): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1378): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1378): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1378): createShortcutInfo...
W/ResourceType( 1378): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1378): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1378): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1378): createShortcutInfo...
D/KeyguardModel( 1378): handleShortcutListChanged...
I/LGEmail ( 6819): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/AndroidRuntime( 6793): Shutting down VM
D/LGEmail ( 6819): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
I/[SystemUI]TimeTickManager( 1378): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1378): called onTimeUpdated()
I/[SystemUI]Clock( 1378): called onTimeUpdated()
I/LgeClockWidgetControlView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
I/[SystemUI]DateView( 1378): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1378): handleTimeUpdate
I/NotificationService(  853): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  853): Receieved: android.intent.action.PACKAGE_REMOVED
W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/TaskPersister(  853): removeObsoleteFile: deleting file=220_task.xml
D/TaskPersister(  853): removeObsoleteFile: deleting file=220_task_thumbnail.png
I/PackageChangeReceiver( 6819): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
W/ResourceType(  853): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6870 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/AppUp4:AppBoxCP( 6870): onCreate
W/AppUp4:DB( 6870):  [AppBoxDatabaseHelper] construct
E/SQLiteDatabase( 6870): Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
E/SQLiteDatabase( 6870): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 6870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 6870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 6870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 6870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 6870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 6870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 6870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 6870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6870): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6870): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/SQLiteDatabase( 6870): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 6870): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 6870): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 6870): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 6870): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 6870): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 6870): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 6870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6870): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6870): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 6870): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6870): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6870): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 6870): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/AndroidRuntime( 6870): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 6870): FATAL EXCEPTION: main
E/AndroidRuntime( 6870): Process: com.lge.appbox.client, PID: 6870
E/AndroidRuntime( 6870): java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6870): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 6870): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 6870): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 6870): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 6870): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 6870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6870): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6870): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 6870): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6870): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6870): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 6870): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 6870): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 6870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 6870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 6870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 6870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 6870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 6870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 6870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 6870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6870): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6870): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/AndroidRuntime( 6870): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 6870): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 6870): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 6870): 	... 11 more
E/DropBoxManagerService(  853): Can't write: system_app_crash
E/DropBoxManagerService(  853): java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  853): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  853): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  853): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  853): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  853): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  853): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
E/DropBoxManagerService(  853): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  853): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  853): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  853): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  853): 	... 5 more

```
