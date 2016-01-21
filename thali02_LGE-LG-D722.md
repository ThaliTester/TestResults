#### Test 564496600f5d794_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/AndroidRuntime( 6036): 
D/AndroidRuntime( 6036): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6036): CheckJNI is OFF
D/AlertService( 5802): Beginning updateAlertNotification
D/AlertService( 5802): No fired or scheduled alerts
I/NotificationManager( 5802): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5802): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5802): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5802): No events found starting within 1 week.
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
--------- beginning of system
I/ActivityManager(  863): Killing 5802:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_10013/pid_5802/cgroup.procs: No such file or directory
D/AndroidRuntime( 6036): Calling main entry com.android.commands.am.Am
I/ActivityManager(  863): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  863): setTaskToReturnTo : TaskRecord{3c45a27d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  863): setTaskToReturnTo : TaskRecord{3c45a27d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  863): AppWindowTokenEx init.. 
D/ContextHelper(  863): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  863): Focus left window: Window{1888eced u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6036): Shutting down VM
I/[LGHome]EVENT( 1950): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  863): check instance of lgWin Window{367ea31f u0 Starting com.test.thalitest}
I/ActivityManager(  863): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6059 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1950): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/art     (  306): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 337us total 28.451ms
I/art     (  306): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 24.891ms
I/HotwordDetector( 2034): Closing mic
I/MicrophoneInputStream( 2034): mic_close com.google.android.apps.gsa.speech.audio.u@7fb4980
V/AudioRecord( 2034): stop()
D/AudioRecord( 2034): AudioRecord->stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
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
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb384f000
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 26.637ms
,V/audio_hw_primary(  279): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  279): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  279): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  279): disable_audio_route: reset and update mixer path: audio-record
I/[LGHome]EVENT( 1950): [Launcher.java:5214:onStop()]onStop
V/audio_hw_primary(  279): disable_audio_route: exit
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
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb384f000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioRecord( 2034): stop()
V/AudioRecord( 2034): stop()
V/AudioRecord( 2034): stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 17
V/AudioPolicyManager(  279): closeInput(17)
V/AudioFlinger(  279): releasing 16 from 2034 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/AudioFlinger(  279): closeInput() 17
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  863): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1369): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2034): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): ThreadBase::exit
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): RecordThread 0xb384f000 exiting
V/AudioSystem( 3200): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2213): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1769): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2060): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb546e240)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
I/WindowStateAnimator(  863): Starting window displayed
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): releaseInput() exit
I/HotwordRecognitionRnr( 2034): Stopping hotword detection.
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  279): removeClient_l() pid 2034, calling pid 279
I/HotwordRecognitionRnr( 2034): Hotword detection finished
I/SystemUI[Framework](  863): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  863): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  863): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  863): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  863): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3eeee134,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  863): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1369): draw background and invalidate : color = 13000000
D/BarTransitions( 1369): draw background and invalidate : color = 11111111
D/ContextHelper( 6059): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6059): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  863): Killing 5272:com.google.android.talk/u0a61 (adj 15): empty #11
I/LibraryLoader( 6059): Time to load native libraries: 2 ms (timestamps 4547-4549)
I/LibraryLoader( 6059): Expected native library version number "",actual native library version number ""
W/libprocessgroup(  863): failed to open /acct/uid_10061/pid_5272/cgroup.procs: No such file or directory
V/WebViewChromiumFactoryProvider( 6059): Binding Chromium to main looper Looper (main, tid 1) {302c110b}
I/LibraryLoader( 6059): Expected native library version number "",actual native library version number ""
I/chromium( 6059): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6059): Initializing chromium process, singleProcess=true
W/art     ( 6059): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6059): ApplicationContext is null in ApplicationStatus
W/chromium( 6059): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6059): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6059): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6059): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6059): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6059): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6059): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6059): Remote Branch: 
I/Adreno-EGL( 6059): Local Patches: 
I/Adreno-EGL( 6059): Reconstruct Branch: 
,V/AudioPolicyService(  279): registerClient() client 0xb4027220, uid 10316
,D/BluetoothManagerService(  863): Message: 20
D/BluetoothManagerService(  863): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34c022e9:true
,D/BluetoothAdapterService(101233383)( 2060): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@77706f5
V/AlarmManager(  863): RTC_WAKEUP set : Alarm{1202f934 type 0 when 1453370522669 com.android.vending} when 1453370522669
,D/Finsky  ( 5918): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  863): android: cancelAsUser(2) by android
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/art     ( 6059): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6059): onDetachedFromWindow called when already detached. Ignoring
,D/libc-netbsd( 5918): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5918): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5918): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5918): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5918): propertyValue:false
D/libc-netbsd( 5918): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5918): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/SystemWebViewEngine( 6059): CordovaWebView is running on device made by: LGE
W/art     ( 6059): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6059): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 6059): Activity.onPostResume() called 
,D/OpenGLRenderer( 6059): Render dirty regions requested: true
I/OpenGLRenderer( 6059): Initialized EGL, version 1.4
D/OpenGLRenderer( 6059): Enabling debug mode 0
,D/Atlas   ( 6059): Validating map...
,D/SplitWindow(  863): check instance of lgWin Window{65a45d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6059): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  863): Focus entered window: Window{65a45d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 95188929083; DSPS: 3219219; Offset : -3064719421
,W/InputMethodManagerService(  863): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  863): Displayed com.test.thalitest/.MainActivity: +1s209ms
I/Timeline(  863): Timeline: Activity_windows_visible id: ActivityRecord{ad67572 u0 com.test.thalitest/.MainActivity t222} time:95206
I/Timeline( 6059): Timeline: Activity_idle id: android.os.BinderProxy@16112756 time:95220
,D/libc-netbsd( 5918): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5918): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/BindingManager( 6059): Cannot call determinedVisibility() - never saw a connection for the pid: 6059
,D/JsMessageQueue( 6059): Set native->JS mode to OnlineEventsBridgeMode
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  863): android: cancelAsUser(2) by android
,I/qtaguid ( 5918): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5918): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5918): untagSocket(41) failed with errno -22
D/Finsky  ( 5918): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  863): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6126 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  863): android: cancelAsUser(2) by android
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ResourcesManager( 6126): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6126): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6126): VM with version 2.1.0 has multidex support
I/MultiDex( 6126): install
,I/MultiDex( 6126): VM has multidex support, MultiDex support library is disabled.
,I/qtaguid ( 5918): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5918): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5918): untagSocket(41) failed with errno -22
D/jxcore_app_log( 6059): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622772224
V/JNIHelp ( 6126): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/chromium( 6059): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ActivityThread( 6126): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6126): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ab723d5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6126): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6126): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6126): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 6126): Reading stored module config
,I/art     ( 6059): CheckpointMarkThreadRoots callback created = 0x9a1dd470
D/ChimeraCfgMgr( 6126): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/SQLiteConnectionPool( 4268): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/WearableService( 1733): callingUid 10006, callindPid: 1733
,E/MDM     ( 1733): [136] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/art     ( 6059): CheckpointMarkThreadRoots callback created = 0x9a1dd450
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4268): Restart initialization of location
I/art     ( 6059): Background partial concurrent mark sweep GC freed 7582(709KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 11MB/19MB, paused 5.548ms total 69.181ms
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,I/art     ( 5526): Explicit concurrent mark sweep GC freed 8198(411KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 456us total 46.080ms
,D/NativeLibraryUtils( 6126): Install completed successfully. count=14 extracted=0
,I/art     ( 5918): CheckpointMarkThreadRoots callback created = 0xb057e380
,D/CAR.SERVICE( 6126): Connecting to CarCallService...
,I/art     ( 5918): CheckpointMarkThreadRoots callback created = 0xb057e340
I/art     ( 6126): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6126): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6126): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6126): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6126): Creating a new PhoneAdapter instance
W/ActivityManager(  863): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6126): setListener: com.google.android.gms.car.dn@2c4ea0a8
W/ActivityManager(  863): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6126): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6126): Starting CarCallService with initial phone null
I/NotificationManager( 6126): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6126): Package validated; name: com.android.vending
,I/NotificationManager( 5918): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5918): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/art     (  863): Explicit concurrent mark sweep GC freed 33876(1640KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 1.976ms total 194.881ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  863): android: cancelAsUser(2) by android
,I/qtaguid ( 5918): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5918): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5918): untagSocket(41) failed with errno -22
,W/ResourcesManager( 5918): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5918): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5918): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5918): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  863): RTC_WAKEUP set : Alarm{149633b6 type 0 when 1453370525636 com.android.vending} when 1453370525636
,D/Finsky  ( 5918): [734] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1733): client connected with version: 8296000
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  863): android: cancelAsUser(2) by android
,D/Finsky  ( 5918): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5918): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 5918): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5918): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5918): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5918): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 5918): propertyValue:false
I/ActivityManager(  863): Process com.android.gallery3d (pid 5893) has died
,W/jxcore-log( 6059): Initializing JXcore engine
,W/jxcore-log( 6059): JXcore engine is ready
I/ActivityManager(  863): Process com.android.contacts (pid 5396) has died
,W/Thread-736( 6151): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7723]" dev="sockfs" ino=7723 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-736( 6151): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-736( 6151): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6449]" dev="sockfs" ino=6449 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-736( 6151): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-736( 6151): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-736( 6151): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[29979]" dev="sockfs" ino=29979 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6059): Starting JXcore engine
,I/ActivityManager(  863): Process com.lge.lockscreensettings (pid 5415) has died
W/jxcore-log( 6059): Platform android
W/jxcore-log( 6059): 
,W/jxcore-log( 6059): Process ARCH arm
W/jxcore-log( 6059): 
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  863): RTC_WAKEUP set : Alarm{1e20f7bc type 0 when 1453370527022 com.google.android.googlequicksearchbox} when 1453370527022
,W/art     ( 2034): Verification of void com.google.android.apps.gsa.extradex.attemptedsearchhistory.a$5.run() took 142.415ms
,I/jxcore-log( 6059): JXcore Cordova bridge is ready!
I/jxcore-log( 6059): 
W/jxcore-log( 6059): JXcore engine is started
I/jxcore-log( 6059): Toggling radios to true
I/jxcore-log( 6059): 
,D/BluetoothAdapter( 6059): enable(): BT is already enabled..!
D/WifiServiceImplEx(  863): setWifiEnabled: true pid=6059, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  863): setWifiEnabled: true pid=6059, uid=10316
D/WifiServiceImplEx(  863): disconnect pid=6059, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  863): reconnect pid=6059, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6059): Radios toggled
I/jxcore-log( 6059): 
I/jxcore-log( 6059): My device name is: LGE-LG-D722
I/jxcore-log( 6059): 
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2653): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2653): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  863): WifiStateMachine: Leaving Connected state
,D/WfdsMonitor( 1856): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  863): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/LGWifiP2pService(  863): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  863): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  863): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  274): Clearing all IP addresses on wlan0
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1733): Read error: ssl=0xaaedfe00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1733): SSL shutdown failed: ssl=0xaaedfe00: I/O error during system call, Broken pipe
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 10
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  863): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  863): ignoring duplicate network state non-change
D/WifiHS20(  863): hidePasspointNotification off =false
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  863): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService(  863): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:07.634 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): ValidatedState{ when=-6ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): DefaultState{ when=-23ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): Forcing reevaluation
,D/WifiServiceExtension( 1856): isInternetCheckAvailable return false
I/ActivityManager(  863): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6214 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,E/WifiStateMachine(  863): Start Disconnecting Watchdog 1
D/WifiHS20(  863): hidePasspointNotification off =false
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  863): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  863): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2653): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:07.726 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/CommandListener(  274): Clearing all IP addresses on wlan0
D/ConnectivityService(  863): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  863): disableDataServiceNotify
D/DSQN    (  863): stop dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/WifiHS20(  863): hidePasspointNotification off =false
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1856): isInternetCheckAvailable return false
,I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:07.739 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/ConnectivityService(  863): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiNetworkAgent(  863): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  863): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): Disconnected - quitting
D/Nat464Xlat(  863): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/WifiHS20(  863): hidePasspointNotification off =false
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:07.765 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524292
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/CSLegacyTypeTracker(  863): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/CSLegacyTypeTracker(  863): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:07.773 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/DhcpStateMachine(  863): StoppedState
D/DhcpStateMachine(  863): StoppedState{ when=-69ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  863): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  863): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/QCNEJ   ( 1906): |CORE| No family connected
D/ConnectivityService(  863): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  863): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  863): MasterInitialState.processMessage what=3
D/Tethering(  863): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1906): |CORE| No family connected
I/QCNEJ   ( 1906): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1906): |CORE| sendDefaultNwMsg: default = -1
D/ConnectivityService(  863): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateDISCONNECTED
D/NetworkManagementService(  863): Removing idletimer
D/TelephonyNetworkFactory-1( 1769): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateSCANNING
D/TelephonyNetworkFactory-1( 1769):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  863): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  863):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,W/Settings(  863): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6214): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6214): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6214): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6214): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6214): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/IndexDatabaseHelper( 6214): Using schema version: 115
I/IndexDatabaseHelper( 6214): Index is fine
,V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
I/ActivityManager(  863): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6235 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6235): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6235): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6235): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
I/PCSuite ( 6235): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6235): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6235): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  863): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6260 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6260): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6260): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6260): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6260): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6260): MmsConfig.loadFromDatabase
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2653): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/Babel_SMS( 6260): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6260): MmsConfig.loadFromResources
E/Babel_SMS( 6260): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6260): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/LocSvc_java(  863): onReceive
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:08.879 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:08.885 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2653): wlan0: Associated with c0:ff:d4:d3:aa:48
D/SensorManager( 6260): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6260): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6260): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6260): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6260): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6260): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6260): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6260): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6260): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6260): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6260): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6260): found sensor: LGE Orientation Sensor, handle=49
D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateASSOCIATING
,D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:08.923 DNS addrs= 0.0.0.0, 0.0.0.0, ,
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:08.925 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2653): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2653): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateGROUP_HANDSHAKE
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/WifiServiceExtension(  863): setVHTCapabilityType  : false
,D/SensorManager( 6260): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6260): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6260): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6260): found sensor: Motion Accel, handle=46
I/WifiServerServiceExt(  863): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  863): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  863): setSecurityType  : 2
,I/ActivityManager(  863): Process com.google.android.apps.plus (pid 5498) has died
I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:09.001 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/ConnectivityService(  863): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  863): Got NetworkAgent Messenger
D/ConnectivityService(  863): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  863): NetworkAgent connected
,I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:09.017 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1856): isInternetCheckAvailable return false
E/WifiConfigStore(  863): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
,E/WifiConfigStore(  863): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Setting iface cfg
E/WifiStateMachine(  863): Start Dhcp Watchdog 2
D/DhcpStateMachine(  863): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  863): WaitBeforeStartState
D/ConnectivityService(  863): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,W/Settings( 6260): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6260): startup - clean
I/art     ( 6260): CheckpointMarkThreadRoots callback created = 0xb042d4d0
,I/art     ( 6260): CheckpointMarkThreadRoots callback created = 0xb042d4c0
,I/Babel   ( 6260): deleted: false for 0
E/WifiStateMachine(  863): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  863): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  863): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e4ddbe2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  863): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e4ddbe2 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  863): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  863): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  863): DHCP Start wake lock is acquired.
D/CommandListener(  274): Setting iface cfg
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  863): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateCOMPLETED
D/ConnectivityService(  863): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  863): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  863): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  863): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  863): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  863): ignoring duplicate network state non-change
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  863): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/WifiServiceExtension( 1856): isInternetCheckAvailable return false
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:09.163 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  863): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine(  863): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:09.179 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiHS20(  863): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  863): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1906): |CORE| CNE, received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1856): isInternetCheckAvailable return false
I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:09.183 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1906): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:09.2 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1906): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,E/ConnectivityService(  863): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  863): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  863): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  274): netlink response contains error (File exists)
D/ConnectivityService(  863): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  863): addLocalRoutetoDefaultNetwork
,D/ConnectivityService(  863): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  863): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = true, mWifiLevel = 2
D/Nat464Xlat(  863): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  863): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  863): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  863):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  863):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  863): currentScore = 0, newScore = 20
D/ConnectivityService(  863):    accepting network in place of null
D/ConnectivityService(  863): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    (  863): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  863):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/TelephonyNetworkFactory-1( 1769): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1769):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
E/ConnectivityService(  863): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  863): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  863): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  863): [e] list.add(nai) empty : false size: 1
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = true, mWifiLevel = 2
D/Tethering(  863): MasterInitialState.processMessage what=3
D/ConnectivityService(  863): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1906): |CORE| No family connected
I/QCNEJ   ( 1906): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  863): validation of new default Network = false
D/ConnectivityService(  863): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  863): enableDataServiceNotify 
D/DSQN    (  863): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): [LWD] Start DNSResolver start to wait
I/QCNEJ   ( 1906): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSig,nalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): [LWD] wait 500ms before dns check
D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
W/AudioCapabilities( 6260): Unsupported mime audio/x-lg-flac
D/ConnectivityService(  863): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524290
W/AudioCapabilities( 6260): Unsupported mime audio/adpcm
W/AudioCapabilities( 6260): Unsupported mime audio/g726
W/AudioCapabilities( 6260): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6260): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6260): Unsupported mime video/mjpg
I/DSQN    ( 6307): DSQN samuel.seo ver 141203
E/DSQN    ( 6307): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6307): created command queue thread
I/DSQN    ( 6307): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6307): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/PCSuite ( 6235): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6235): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6235): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/NetworkPolicy(  863): [LG_RESTRICTED] checkMobilePolicy_type()
,W/VideoCapabilities( 6260): Unsupported mime video/theora
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/PCSuite ( 6235): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6235): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6235): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
W/AudioCapabilities( 6260): Unsupported mime audio/evrc
,V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
W/AudioCapabilities( 6260): Unsupported mime audio/qcelp
D/WiFiOffLoadBroadcast( 6214): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6260): Unrecognized profile 2130706433 for video/avc
D/DhcpStateMachine(  863): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  863): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  863): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
I/dhcpcd  ( 6310): version 5.5.6 starting
E/dhcpcd  ( 6310): get_duid: Read-only file system
,W/AudioCapabilities( 6260): Unsupported mime audio/amr-wb-plus
,V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6260): Unsupported mime audio/qcelp
W/AudioCapabilities( 6260): Unsupported mime audio/evrc
D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
W/VideoCapabilities( 6260): Unsupported mime video/mp4v-esdp
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/dhcpcd  ( 6310): wlan0: rebinding lease of 192.168.1.134
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
I/VideoCapabilities( 6260): Unsupported profile 4 for video/mp4v-es
,V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
I/dhcpcd  ( 6310): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
W/VideoCapabilities( 6260): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6260): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6260): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6260): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/vclib   ( 6260): onServiceConnected
W/Babel   ( 6260): Attempted to change video mute state without an active call.
D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
I/NotificationManager( 6260): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/dhcpcd  ( 6310): wlan0: leased 192.168.1.134 for 86400 seconds
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
I/PCSuite ( 6235): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6235): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
,I/PCSuite ( 6235): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6235): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): [LWD] DNSResolver start dns
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  863): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  863): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  863): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  863): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  863): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  863): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  863): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  863): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  863): RunningState
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out(  863): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CAR.SERVICE( 6126): mConnectedToCar = false, abort
,I/DSQN    ( 6307): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6307): restart monitoring
I/DSQN    ( 6307): dsqn report finish
D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  863): DSQM DsqnNotification wlan0  1
D/DSQN    (  863): start to monitor internet connection
E/ActivityThread( 6126): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@150a788e that was originally bound here
E/ActivityThread( 6126): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@150a788e that was originally bound here
E/ActivityThread( 6126): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6126): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6126): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6126): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6126): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6126): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6126): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6126): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6126): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6126): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6126): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6126): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6126): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6126): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6126): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6126): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6126): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6126): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6126): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6126): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6126): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6126): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6126): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6126): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2e5f40cb that was originally bound here
E/ActivityThread( 6126): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2e5f40cb that was originally bound here
E/ActivityThread( 6126): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6126): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6126): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6126): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6126): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6126): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6126): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6126): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6126): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6126): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6126): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6126): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6126): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6126): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6126): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6126): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6126): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6126): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6126): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6126): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6126): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6126): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  863): Unbind failed: could not find connection for android.os.BinderProxy@2731f98f
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 10:02:09 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453370529815], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453370529793]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1856): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): Validated
D/ConnectivityService(  863): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  863):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  863): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  863): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  863): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  863): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524290
I/WifiServerServiceExt(  863): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyNetworkFactory-1( 1769): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  863): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1769):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  863):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  863): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  863): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6347 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  271): 
I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  863): onReceive
D/LocSvc_java(  863): got connectivity action
D/LocSvc_java(  863): broadcast - no network connections
D/LocSvc_java(  863): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
,D/LocSvc_java(  863): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  863): onReceive
D/LocSvc_java(  863): got connectivity action
D/LocSvc_java(  863): broadcast - no network connections
D/LocSvc_java(  863): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  863): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  863): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  863): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  863): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  863): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  863): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  863): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  863): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  863): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  863): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  863): identical MTU - not setting
D/Nat464Xlat(  863): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  863): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  863): enableDataServiceNotify 
D/DSQN    (  863): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524295
I/QCNEJ   ( 1906): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:10.983 DNS addrs= 192.168.1.1, 0.0.0.0, 
,D/GpsLocationProvider(  863): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  863): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DSQN    (  863): dsqn is running restart
I/DSQN    ( 6374): DSQN samuel.seo ver 141203
E/DSQN    ( 6374): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6374): created command queue thread
I/DSQN    ( 6374): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6374): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/MusicStore( 6347): Database version: 120
,I/ActivityManager(  863): Process com.android.vending (pid 5918) has died
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6347): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6347): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6347): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6347): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6347): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6347): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,W/ActivityThread( 6347): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6347): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22950584: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6347): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6347): GMSCore installation verified
,I/ConfigStore( 6347): Config Database version: 1
,W/art     ( 6347): Suspending all threads took: 13.259ms
,I/MediaRouter( 6347): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6347): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6347): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6347): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  863): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6402 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6347): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6347): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 6347): com.google.android.music: cancel(1061) by com.google.android.music
,I/QCNEJ   ( 1906): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1906): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 11:02:12.055 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6402): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6402): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6402): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/WifiInternetCheck(  863): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  863): onReceive
D/LocSvc_java(  863): got connectivity action
D/LocSvc_java(  863): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  863): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  863): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  863): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  863): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  863): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/NetworkMonitor( 6347): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider(  863): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NotificationManager( 2034): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/LGEmail ( 6402): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6402): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  863): Process com.google.android.talk (pid 6260) has died
,D/eas_req ( 6402): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  863): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6435 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 6402): JNI_OnLoad()
I/HubEmail( 6402): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6402): registerNatives()
I/HubEmail( 6402): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6402): registerNativeMethods()
I/HubEmail( 6402): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6402): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6402): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6435): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6435): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6435): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6435): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6435): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6435): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 6435): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6435): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  863): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6462 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6435): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6435): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6435): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6435): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6435): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6435): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  863): Killing 5981:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10014/pid_5981/cgroup.procs: No such file or directory
V/AlarmManager(  863): ELAPSED_WAKEUP set : Alarm{1ff33b74 type 2 when 105263 com.google.android.gms} when 105263
I/AppUp4:AppBoxCP( 6462): onCreate
W/AppUp4:DB( 6462):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6462):  setFingerPrint start
I/AppUp4:DB( 6462):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6462):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6462):  SDK version = 0
I/AppUp4:DB( 6462):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6462): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6462): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6462): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6462): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6462): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6462): onReceive
I/AppUp4:CustModeStarterReceiver( 6462): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6462): Context : android.app.ReceiverRestrictedContext@2976cbe8
D/AppUp4:CustFacade( 6462): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6462): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6462): begin check event
I/AppUp4:CustModeStarterReceiver( 6462): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6462): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6462): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6462): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6462): handleAsyncCustNotification do not startCustService
I/ActivityManager(  863): Killing 6126:com.google.android.gms:car/u0a6 (adj 15): empty #11
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
W/libprocessgroup(  863): failed to open /acct/uid_10006/pid_6126/cgroup.procs: No such file or directory
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  863): propertyValue:false
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  863): propertyValue:false
I/LgeMiscReceiver( 3200): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3200): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3200): networkInfo.isConnected() = false
,I/DSQN    ( 6374): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6374): restart monitoring
D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    (  863): DSQM DsqnNotification wlan0  1
D/DSQN    (  863): start to monitor internet connection
I/DSQN    ( 6374): dsqn report finish
V/WifiInternetCheck(  863): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager(  863): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6486 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6486): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6486): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6486): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  863): Killing 6214:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_1000/pid_6214/cgroup.procs: No such file or directory
,I/CheckinService( 4268): Checkin interval check for package: unspecified last checkin: 1453370507042 min interval config: 0 actual interval: 26684
,V/DownloadManager( 3218): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3218): DownloadService onCreate
,D/PhoneMonitor( 6486): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6486): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6486): [parse] Load xml
,V/TelephonyAutoProfiling( 6486): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6486): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/ActivityManager(  863): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6509 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/CheckinService( 4268): Checking schedule, now: 1453370533770 next: 1453370536912
I/CheckinService( 4268): active receiver: disabled
I/DownloadManager( 3218): in removeSpuriousFiles
I/NotificationManager( 3218): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3218): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/PhoneMonitor( 6486): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@3ab723d5 on behalf of 3218
,I/DownloadManager( 3218): in trimDatabase
V/DownloadManager( 3218): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3218): DownloadService onStartCommand
V/DownloadManager( 3218): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@2b51eadb on behalf of 3218
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@27d1e978 on behalf of 3218
,V/DownloadManager( 3218): DownloadService onDestroy
,I/ActivityManager(  863): Killing 5629:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5016): android.os.DeadObjectException
,W/System.err( 5016): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5016): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5016): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5016): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5016): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391),
W/System.err( 5016): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5016): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5016): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5016): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5016): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5016): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5016): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5016): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5016): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5016): android.os.DeadObjectException
W/System.err( 5016): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5016): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5016): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5016): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5016): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5016): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5016): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5016): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5016): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5016): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5016): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5016): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5016): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5016): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  863): failed to open /acct/uid_10089/pid_5629/cgroup.procs: No such file or directory
W/ActivityManager(  863): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/WeatherAncestor( 2844): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:14
I/ActivityManager(  863): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6531 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UpdateThreadPoolManager( 2844): 2 : This is isUpdating : false
D/WeatherAncestor( 2844): connectivity changed - connection : true
D/Weather_cast( 2844): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2844): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:14
,I/art     (  306): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 355us total 28.644ms
D/WeatherService( 2844): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/art     (  306): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 323us total 23.925ms
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 22.065ms
,I/ActivityManager(  863): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6556 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  863): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2844): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2844): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2844): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6531): Quickset Services start...
,I/UEI.SmartControl( 6531): Manufacture = LGE
D/UEI.SmartControl( 6531): File observer start...
E/UEI.SmartControl( 6531): IR Port is disabled: false
D/UEI.SmartControl( 6531): Starting file observer...
D/UEI.SmartControl( 6531): Extracting JNI libs...
D/UEI.SmartControl( 6531): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6531): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6531): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6531): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/art     (  863): Explicit concurrent mark sweep GC freed 83987(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.193ms total 188.692ms
,I/UEI.SmartControl( 6531): --- Selecting new region: 2
I/UEI.SmartControl( 6531): -- Running on KitKat(19) and above! JNI will be used.
,W/ResourcesManager( 6556): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6531): Platform has CIR...
D/UEI.SmartControl( 6531): NO CIR support, need to check package...
I/UEI.SmartControl( 6531): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 6531): QS Service created
E/UEI.SmartControl( 6531): QS start get config
,D/UEI.SmartControl( 6531): Loading JNI Libs...
,D/UEI.SmartControl( 6531):  configuring local db...
,I/Babel_SMS( 6556): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6556): MmsConfig.loadMmsSettings
I/Babel_SMS( 6556): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6556): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6556): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6556): MmsConfig.loadFromResources
E/Babel_SMS( 6556): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6556): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/UEI.SmartControl( 6531):  ---- Has DB8: true
,D/UEI.SmartControl( 6531): QS start statue = true Error code = 0
D/UEI.SmartControl( 6531): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6531): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6531): IRRCDataComm has AudioManager!!!!.
,D/SensorManager( 6556): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6556): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6556): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6556): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6556): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6556): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6556): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6556): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6556): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6556): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6556): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6556): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6556): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6556): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6556): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6556): found sensor: Motion Accel, handle=46
W/irrc_jni( 6531): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6531): IrrcClient ++ 
,D/irrcClient( 6531): getIrrcService ++ 
D/irrcClient( 6531): getIrrcService -- 
D/irrcClient( 6531): IrrcClient -- 
W/irrc_jni( 6531): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6531): Services init done
,I/art     ( 6556): CheckpointMarkThreadRoots callback created = 0xb042d810
I/UEI.SmartControl( 6531): Device manager: loading config....
D/UEI.SmartControl( 6531): QS Service init finished
D/UEI.SmartControl( 6531): QS Service version name: 0.1.73
D/UEI.SmartControl( 6531): QS Service version code: 1073
D/UEI.SmartControl( 6531): Service requested: Control
D/UEI.SmartControl( 6531): Config is loaded...
,W/Settings( 6556): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6556): startup - clean
,I/art     ( 6556): CheckpointMarkThreadRoots callback created = 0xb042d800
D/UEI.SmartControl( 6531):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6531): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6531): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6531): -----IControl: 11
D/UEI.SmartControl( 6531): Caller: com.lge.qremote
D/UEI.SmartControl( 6531): Internal service binding...
D/UEI.SmartControl( 6531): ------------ IControl registerCallback...
I/UEI.SmartControl( 6531): Registering callback...
D/UEI.SmartControl( 6531): -----IControl: 19
D/UEI.SmartControl( 6531): Caller: com.lge.qremote
I/UEI.SmartControl( 6531): Registering Services Ready callback...
I/UEI.SmartControl( 6531): Notify client services are ready...
D/UEI.SmartControl( 6531): -----IControl: 8
D/UEI.SmartControl( 6531): Caller: com.lge.qremote
,I/Babel   ( 6556): deleted: false for 0
,I/jxcore-log( 6059): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6059): 
,I/ActivityManager(  863): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6590 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 6235:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_1000/pid_6235/cgroup.procs: No such file or directory
,W/AudioCapabilities( 6556): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6556): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6556): Unsupported mime audio/g726
W/AudioCapabilities( 6556): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6556): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6556): Unsupported mime video/mjpg
W/VideoCapabilities( 6556): Unsupported mime video/theora
,W/AudioCapabilities( 6556): Unsupported mime audio/evrc
,W/AudioCapabilities( 6556): Unsupported mime audio/qcelp
W/VideoCapabilities( 6556): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6556): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6556): Unsupported mime audio/qcelp
W/AudioCapabilities( 6556): Unsupported mime audio/evrc
,W/VideoCapabilities( 6556): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6556): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6556): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6556): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6556): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6556): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6556): onServiceConnected
,W/Babel   ( 6556): Attempted to change video mute state without an active call.
D/libc-netbsd( 6556): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6556): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6556): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6556): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6556): propertyValue:false
I/NotificationManager( 6556): com.google.android.talk: cancel(10436) by com.google.android.talk
I/Babel   ( 6556): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  863): Killing 5016:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10106/pid_5016/cgroup.procs: No such file or directory
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6590): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6590): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6590): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6590): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6590): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6590):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6590):   adb logcat -s GAv4
W/GAv4    ( 6590): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ProcessCpuTracker(  863): Skipping unknown process pid 6616
W/ProcessCpuTracker(  863): Skipping unknown process pid 6619
,W/GAv4    ( 6590): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6590): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6590): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6590): Time to load native libraries: 2 ms (timestamps 8289-8291)
,I/LibraryLoader( 6590): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6590): Binding Chromium to main looper Looper (main, tid 1) {1549ac45}
I/LibraryLoader( 6590): Expected native library version number "",actual native library version number ""
I/chromium( 6590): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6590): Initializing chromium process, singleProcess=true
,W/art     ( 6590): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6590): ApplicationContext is null in ApplicationStatus
W/chromium( 6590): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6590): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6590): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6590): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6590): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6590): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6590): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6590): Remote Branch: 
I/Adreno-EGL( 6590): Local Patches: 
I/Adreno-EGL( 6590): Reconstruct Branch: 
I/jxcore-log( 6059): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6059): 
,I/jxcore-log( 6059): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6059): 
V/AudioPolicyService(  279): registerClient() client 0xb4027240, uid 10079
,W/AudioManagerAndroid( 6590): Requires BLUETOOTH permission
I/jxcore-log( 6059): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6059): 
,I/ActivityManager(  863): Process com.google.android.music:main (pid 6347) has died
,I/jxcore-log( 6059): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6059): 
I/NSApplication( 6590): Starting up...
,I/jxcore-log( 6059): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6059): 
I/jxcore-log( 6059): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6059): 
,I/ActivityManager(  863): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6664 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  863): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6683 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 6402:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_10021/pid_6402/cgroup.procs: No such file or directory
,W/ResourcesManager( 6683): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/AlarmManager(  863): RTC_WAKEUP set : Alarm{ab14fd2 type 0 when 1453370536912 com.google.android.gms} when 1453370536912
,V/AlarmManager(  863): RTC_WAKEUP set : Alarm{77e27a0 type 0 when 1453370537245 com.google.android.googlequicksearchbox} when 1453370537245
I/ActivityManager(  863): Killing 6435:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_1000/pid_6435/cgroup.procs: No such file or directory
,I/ActivityManager(  863): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6719 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6719): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6719): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6719): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6719): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ResourcesManager( 6719): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6719): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6719): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6719): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6719): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22950584: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6719): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6719): GMSCore installation verified
I/ConfigStore( 6719): Config Database version: 1
,I/MediaRouter( 6719): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6719): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6719): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6719): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  863): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6754 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6719): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6719): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  863): Killing 6462:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6754): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6754): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6754): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  863): failed to open /acct/uid_10011/pid_6462/cgroup.procs: No such file or directory
,I/NotificationManager( 6719): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6754): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6754): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6754): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  863): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6777 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/HubEmail( 6754): JNI_OnLoad()
I/HubEmail( 6754): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6754): registerNatives()
I/HubEmail( 6754): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6754): registerNativeMethods()
I/HubEmail( 6754): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6754): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  863): Killing 6486:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10038/pid_6486/cgroup.procs: No such file or directory
,W/Settings( 6754): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6777): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6777): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6777): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6777): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6777): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6777): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 6777): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6777): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  863): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6814 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 6777): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6777): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6777): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6777): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6777): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6777): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  863): Killing 6509:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_10051/pid_6509/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6814): onCreate
,W/AppUp4:DB( 6814):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6814):  setFingerPrint start
,I/AppUp4:DB( 6814):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6814):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6814):  SDK version = 0
I/AppUp4:DB( 6814):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6814): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6814): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6814): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6814): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6814): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6814): onReceive
,I/AppUp4:CustModeStarterReceiver( 6814): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6814): Context : android.app.ReceiverRestrictedContext@2976cbe8
D/AppUp4:CustFacade( 6814): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6814): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6814): begin check event
I/AppUp4:CustModeStarterReceiver( 6814): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6814): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6814): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6814): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6814): handleAsyncCustNotification do not startCustService
I/ActivityManager(  863): Killing 6531:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/LgeMiscReceiver( 3200): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3200): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3200): networkInfo.isConnected() = false
W/libprocessgroup(  863): failed to open /acct/uid_10089/pid_6531/cgroup.procs: No such file or directory
,I/ActivityManager(  863): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6839 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  863): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6855 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  863): RTC_WAKEUP set : Alarm{12e06f78 type 0 when 1453370540035 com.android.vending} when 1453370540035
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/PhoneMonitor( 6839): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6839): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6839): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 3218): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3218): DownloadService onCreate
I/DownloadManager( 3218): in removeSpuriousFiles
I/NotificationManager( 3218): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3218): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@1d5708b6 on behalf of 3218
I/DownloadManager( 3218): in trimDatabase
V/DownloadManager( 3218): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@26f82524 on behalf of 3218
I/ActivityManager(  863): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6884 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3218): DownloadService onStartCommand
I/art     (  306): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 29.841ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 316us total 25.972ms
,I/CheckinService( 4268): Checkin interval check for package: unspecified last checkin: 1453370507042 min interval config: 0 actual interval: 33359
V/DownloadManager( 3218): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 21.121ms
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@1ec2fa42 on behalf of 3218
,D/PhoneMonitor( 6839): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6839): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6839): [parse] Load xml
V/TelephonyAutoProfiling( 6839): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6839): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/CheckinService( 4268): Checking schedule, now: 1453370540466 next: 1453370536912
,I/CheckinService( 4268): active receiver: enabled
D/PhoneMonitor( 6839): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/CheckinService( 4268): Preparing to send checkin request
I/EventLogService( 4268): Accumulating logs since 1453370499596
D/Finsky  ( 6855): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     (  863): Explicit concurrent mark sweep GC freed 22670(1157KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.102ms total 169.639ms
,V/DownloadManager( 3218): DownloadService onDestroy
,D/WeatherAncestor( 2844): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:20
,D/UpdateThreadPoolManager( 2844): 2 : This is isUpdating : false
D/WeatherAncestor( 2844): connectivity changed - connection : true
D/Weather_cast( 2844): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2844): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:20
D/WeatherService( 2844): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  863): getTasks: caller 10074 does not hold GET_TASKS; limiting output
I/CheckinRequestBuilder( 4268): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4268): Failed to find provider info for com.google.android.wearable.settings
D/Weather.Utils( 2844): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2844): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2844): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,V/MusicLeanback( 6719): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/LGDMClient( 6777): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6777): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6777): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6777): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/Settings( 6754): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Finsky  ( 6855): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/NetworkStateForAutoUpdateMonitor( 6814): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6814): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6814): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6814): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6814): onReceive
I/AppUp4:CustModeStarterReceiver( 6814): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6814): Context : android.app.ReceiverRestrictedContext@2976cbe8
D/AppUp4:CustFacade( 6814): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6814): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6814): begin check event
I/AppUp4:CustModeStarterReceiver( 6814): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 6777): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LgeMiscReceiver( 3200): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3200): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3200): networkInfo.isConnected() = true
D/PhoneState( 3200): setPdpRejectCasuse : false
D/LGDMClient( 6777): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6777): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/LGDMClient( 6777): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/MobileConnectivityChangeReceiver( 6839): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
W/Settings( 6855): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/MobileConnectivityChangeReceiver( 6839): onReceive CONNECTIVITY_CHANGE networkType=1
W/Settings( 6855): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
V/DownloadManager( 3218): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/NotificationManager( 6855): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3218): DownloadService onCreate
W/ContextImpl( 6777): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/NotificationManager( 3218): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/WeatherAncestor( 2844): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:20
E/LGDMClient( 6777): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6777): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6777): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6777): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/DownloadManager( 3218): in removeSpuriousFiles
V/DownloadManager( 3218): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@1e246f90 on behalf of 3218
D/LGDMClient( 6777): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/DownloadManager( 3218): in trimDatabase
,V/DownloadManager( 3218): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/UpdateThreadPoolManager( 2844): 2 : This is isUpdating : false
D/WeatherAncestor( 2844): connectivity changed - connection : true
D/Weather_cast( 2844): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2844): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:20
D/WeatherService( 2844): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@150a788e on behalf of 3218
V/DownloadManager( 3218): DownloadService onStartCommand
W/ActivityManager(  863): getTasks: caller 10074 does not hold GET_TASKS; limiting output
V/DownloadManager( 3218): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/Weather.Utils( 2844): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2844): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2844): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@2788f4bc on behalf of 3218
,I/art     ( 6683): CheckpointMarkThreadRoots callback created = 0xb042d410
,V/DownloadManager( 3218): DownloadService onDestroy
,I/art     ( 6683): CheckpointMarkThreadRoots callback created = 0xb042d3e0
V/DownloadManager( 3218): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/Ads     ( 6855): Skipping gmscore version check
V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@5398f9a on behalf of 6855
D/Finsky  ( 6855): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6855): [1] Libraries$2.run: Finished loading 1 libraries.
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
,I/ActivityManager(  863): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6943 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/Finsky  ( 6855): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  863): Killing 6719:com.google.android.music:main/u0a81 (adj 15): empty #11
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/libprocessgroup(  863): failed to open /acct/uid_10081/pid_6719/cgroup.procs: No such file or directory
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6855): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/ResourcesManager( 6943): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/Finsky  ( 6855): [840] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6855): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  863): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6963 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 6754:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10021/pid_6754/cgroup.procs: No such file or directory
,W/ResourcesManager( 6963): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6963): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  863): Message: 20
,D/BluetoothManagerService(  863): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1bbe9908:true
D/BluetoothAdapterService(101233383)( 2060): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@77706f5
,D/BluetoothAdapterService(101233383)( 2060): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@77706f5
I/MultiDex( 6963): VM with version 2.1.0 has multidex support
I/MultiDex( 6963): install
I/MultiDex( 6963): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  863): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6984 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/LGMDMManager( 6943): Create singleton instance
I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,V/JNIHelp ( 6963): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/UEI.SmartControl( 6984): Quickset Services start...
,I/AudioManager( 6943): getMode name:com.lge.qremote
I/UEI.SmartControl( 6984): Manufacture = LGE
D/UEI.SmartControl( 6984): File observer start...
E/UEI.SmartControl( 6984): IR Port is disabled: false
D/UEI.SmartControl( 6984): Starting file observer...
D/UEI.SmartControl( 6984): Extracting JNI libs...
D/UEI.SmartControl( 6984): --- this system supports 32-bit or 64-bit only
,I/CheckinService( 4268): Checkin interval check for package: unspecified last checkin: 1453370507042 min interval config: 0 actual interval: 34657
W/ActivityThread( 6963): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6963): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ab723d5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6963): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6963): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6963): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 6963): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6963): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/AudioManager( 6943): getMode name:com.lge.qremote
,W/ContextImpl( 3601): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/UEI.SmartControl( 6984): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6984): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6984): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/WearableService( 1733): callingUid 10006, callindPid: 1733
,D/WVCdm   (  279): Instantiating CDM.
I/WVCdm   (  279): CdmEngine::OpenSession
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
,E/MDM     ( 1733): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4268): Restart initialization of location
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 6963): Install completed successfully. count=14 extracted=0
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/UEI.SmartControl( 6984): --- Selecting new region: 2
I/UEI.SmartControl( 6984): -- Running on KitKat(19) and above! JNI will be used.
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,D/UEI.SmartControl( 6984): Platform has CIR...
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 6984): NO CIR support, need to check package...
I/UEI.SmartControl( 6984): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6984): QS Service created
I/art     ( 6963): Background sticky concurrent mark sweep GC freed 26896(1592KB) AllocSpace objects, 2(32KB) LOS objects, 5% free, 10MB/11MB, paused 3.024ms total 106.381ms
I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  279): PrepareKeyRequest: nonce=2356571108
E/UEI.SmartControl( 6984): QS start get config
,D/UEI.SmartControl( 6984): Loading JNI Libs...
D/UEI.SmartControl( 6984):  configuring local db...
,E/libprocessgroup(  863): failed to kill 1 processes for processgroup 6590
I/ActivityManager(  863): Process com.google.android.apps.magazines (pid 6590) has died
,I/art     ( 6963): CheckpointMarkThreadRoots callback created = 0xb04cbe20
,I/art     ( 6963): CheckpointMarkThreadRoots callback created = 0xaae47e20
,D/UEI.SmartControl( 6984):  ---- Has DB8: true
D/UEI.SmartControl( 6984): QS start statue = true Error code = 0
D/UEI.SmartControl( 6984): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6984): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6984): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6984): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6984): IrrcClient ++ 
D/irrcClient( 6984): getIrrcService ++ 
D/irrcClient( 6984): getIrrcService -- 
D/irrcClient( 6984): IrrcClient -- 
W/irrc_jni( 6984): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6984): Services init done
,D/UEI.SmartControl( 6984): QS Service init finished
,D/UEI.SmartControl( 6984): QS Service version name: 0.1.73
D/UEI.SmartControl( 6984): QS Service version code: 1073
D/UEI.SmartControl( 6984): Service requested: Control
I/UEI.SmartControl( 6984): Device manager: loading config....
,D/UEI.SmartControl( 6984): Config is loaded...
D/UEI.SmartControl( 6984):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6984): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6984): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6984): Internal service binding...
D/UEI.SmartControl( 6984): -----IControl: 11
D/UEI.SmartControl( 6984): Caller: com.lge.qremote
D/UEI.SmartControl( 6984): ------------ IControl registerCallback...
I/UEI.SmartControl( 6984): Registering callback...
D/UEI.SmartControl( 6984): -----IControl: 19
,D/UEI.SmartControl( 6984): Caller: com.lge.qremote
I/UEI.SmartControl( 6984): Registering Services Ready callback...
I/UEI.SmartControl( 6984): Notify client services are ready...
D/UEI.SmartControl( 6984): -----IControl: 8
D/UEI.SmartControl( 6984): Caller: com.lge.qremote
I/AudioManager( 6943): getMode name:com.lge.qremote
I/ActivityManager(  863): Killing 6814:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10011/pid_6814/cgroup.procs: No such file or directory
,I/AudioManager( 6943): getMode name:com.lge.qremote
I/AudioManager( 6943): getMode name:com.lge.qremote
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 115189739440; DSPS: 3874607; Offset : -3064761317
,I/dex2oat ( 7032): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/dex2oat ( 7032): dex2oat took 167.394ms (threads: 4)
,I/Adreno-EGL( 6963): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6963): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6963): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6963): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6963): Remote Branch: 
I/Adreno-EGL( 6963): Local Patches: 
I/Adreno-EGL( 6963): Reconstruct Branch: 
,I/Adreno-EGL( 6963): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6963): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6963): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6963): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6963): Remote Branch: 
I/Adreno-EGL( 6963): Local Patches: 
I/Adreno-EGL( 6963): Reconstruct Branch: 
,I/WVCdm   (  279): CdmEngine::OpenSession
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=2808651488
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MusicWidget( 2777): mDelayedStopHandler : unbind
I/MusicBrowser( 2213): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2213): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2213): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2213): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2213): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2213): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  863):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@117e1d71com.lge.music.MediaPlaybackService$6@16112756
D/MusicBrowser( 2213): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2213): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2213): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@3de0be94
I/MusicBrowser( 2213): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2213): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2213): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2213): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2213): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2213): reset
V/MediaPlayer[Native]( 2213): setListener
V/MediaPlayer[Native]( 2213): disconnect
V/MediaPlayer[Native]( 2213): destructor
,V/AudioFlinger(  279): releasing 19 from 2213 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/MediaPlayer[Native]( 2213): disconnect
D/MusicBrowser( 2213): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2213): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2213): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2213): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
,I/MusicBrowser( 2213): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2213): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2213): [SmartShareManagerClient] unregisterListener: 567157719
W/SmartShareClient( 2213): [SmartShareManagerClient] unregisterListener invalid listener: 567157719
I/SmartShareClient( 2213): [SmartShareManagerClient] terminate service: 2213/MediaPlaybackService/1014135002
E/HomeCloudIF( 2213): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2213): [SmartShareManagerClient] unbindService context:android.app.Application@2faf4c4
V/CloudHub( 2213): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2213): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2213): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2213): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2213): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  863): Killing 6884:com.lge.drmservice/u0a51 (adj 15): empty #11
I/CloudHub( 2213): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29995
W/libprocessgroup(  863): failed to open /acct/uid_10051/pid_6884/cgroup.procs: No such file or directory
,I/jxcore-log( 6059): Test app app.js loaded
I/jxcore-log( 6059): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6059): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6059): BLE advertisement is supported
I/jxcore-log( 6059): 
I/chromium( 6059): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): L3 Terminate.
I/Adreno-EGL( 6963): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6963): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6963): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6963): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6963): Remote Branch: 
I/Adreno-EGL( 6963): Local Patches: 
I/Adreno-EGL( 6963): Reconstruct Branch: 
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/CheckinRequestBuilder( 4268): Classify the device as Phone.
,D/libc-netbsd( 4268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
,D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 4268): propertyValue:false
,D/libc-netbsd( 4268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4268): Sending checkin request (9734 bytes)
,I/CheckinRequestBuilder( 4268): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4268): Failed to find provider info for com.google.android.wearable.settings
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     ( 5526): Explicit concurrent mark sweep GC freed 1907(72KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 440us total 32.084ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4268): Classify the device as Phone.
,I/CheckinTask( 4268): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4268): Checking schedule, now: 1453370547401 next: 1453897796397
I/CheckinService( 4268): active receiver: disabled
,I/CheckinService( 4268): Checking schedule, now: 1453370547437 next: 1453897796397
,I/CheckinService( 4268): active receiver: disabled
D/CheckinService( 4268): Recording last checkin time for package unspecified as 1453370547446
I/ActivityManager(  863): Killing 6777:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_1000/pid_6777/cgroup.procs: No such file or directory
,V/SetupWizard( 6839): Connected to Gservices successfully
I/ActivityManager(  863): Killing 6664:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10048/pid_6664/cgroup.procs: No such file or directory
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 6984): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]QPairHandler( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1906): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  863): Reconfiguring input devices.  changes=0x00000010
,W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1950): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1950): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1950): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/ActivityManager(  863): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7126 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/administrator(  863): Handling package changes for user 0
,W/ResourcesManager( 6556): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6556): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NotificationManager( 6556): com.google.android.talk: cancel(8) by com.google.android.talk
V/JNIHelp ( 6556): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 7126): onCreate
W/AppUp4:DB( 7126):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7126):  setFingerPrint start
I/AppUp4:DB( 7126):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7126):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7126):  SDK version = 0
I/AppUp4:DB( 7126):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7126): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7126): onReceive
,I/AppUp4:CustModeStarterReceiver( 7126): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7126): Context : android.app.ReceiverRestrictedContext@2c1b7285
D/AppUp4:CustFacade( 7126): isCustomizationCompleted : false
W/System  ( 6556): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6556): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  863): Process com.google.android.apps.plus (pid 6683) has died
,D/AppUp4:CustFacade( 7126): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7126): begin check event
I/AppUp4:CustModeStarterReceiver( 7126): Event For Nothing, skip.
,I/NotificationService(  863): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
I/ActivityManager(  863): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7151 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/LCardEmulationManager( 1825): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1825): getDefaultRoute
D/BackupManagerService(  863): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  863): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager(  863): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/BackupManagerService(  863): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  863): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  863): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@efac11f
,W/ResourcesManager( 7151): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7151): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7151): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/art     (  863): Explicit concurrent mark sweep GC freed 34653(1607KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.967ms total 213.029ms
W/ResourceType(  863): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1950): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppConfig( 7151): Total System Memory = 906309632
I/GalleryUtils( 7151): Application Heap = 96 MB
D/LocationProviderProxy(  863): applying state to connected service
,I/AppConfig( 7151): App Tier : NOT_DEF
,D/SystemHelper( 7151): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  863): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7171 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7171): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7171): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7171): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7171): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7171): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/SystemConfig( 7171): BUILD Country: EU
I/SystemConfig( 7171): BUILD Operator: OPEN
,I/ActivityManager(  863): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7197 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 6855:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_10036/pid_6855/cgroup.procs: No such file or directory
,I/SystemConfig( 7171): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7171): existFile = false
,I/SystemConfig( 7171): canReadFile = false
I/SystemConfig( 7171): systemFeature RCS result false
D/SystemConfig( 7171): refreshRcsSupport() :false
I/LockScreenSettings( 7197): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7197): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7197): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7197): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7197): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,D/LockScreenSettings( 7197): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  863): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7214 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 2213:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  279): 2213 died, releasing its sessions
V/AudioFlinger(  279):  pid 1769 @ 0
V/AudioFlinger(  279):  pid 3200 @ 1
V/AudioFlinger(  279):  pid 3200 @ 2
,W/libprocessgroup(  863): failed to open /acct/uid_10028/pid_2213/cgroup.procs: No such file or directory
,W/ResourcesManager( 7214): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  863): Process com.google.android.gms.unstable (pid 6963) has died
,I/UpdateIcingCorporaServi( 2034): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  863): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7239 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 2034): UpdateCorporaTask done [took 87 ms] updated apps [took 87 ms] 
,D/Finsky  ( 7239): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7239): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7239): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7239): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7239): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3218): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3218): created cursor android.database.sqlite.SQLiteCursor@2e5f40cb on behalf of 7239
D/Finsky  ( 7239): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7239): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7239): Skipping gmscore version check
,I/ActivityManager(  863): Killing 6984:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6943): android.os.DeadObjectException
,W/System.err( 6943): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6943): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6943): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6943): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6943): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6943): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6943): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6943): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6943): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6943): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6943): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6943): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6943): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6943): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6943): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6943): android.os.DeadObjectException
W/System.err( 6943): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6943): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6943): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6943): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6943): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6943): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6943): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6943): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6943): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6943): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6943): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6943): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6943): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6943): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6943): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  863): failed to open /acct/uid_10089/pid_6984/cgroup.procs: No such file or directory
,W/ActivityManager(  863): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/PackageBroadcastService( 4268): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Finsky  ( 7239): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/PackageBroadcastService( 4268): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  863): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7297 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 7239): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Icing   ( 4268): updateResources: need to parse f{com.google.android.gms}
,D/UEI.SmartControl( 7297): Quickset Services start...
,I/UEI.SmartControl( 7297): Manufacture = LGE
D/UEI.SmartControl( 7297): File observer start...
E/UEI.SmartControl( 7297): IR Port is disabled: false
D/UEI.SmartControl( 7297): Starting file observer...
D/UEI.SmartControl( 7297): Extracting JNI libs...
D/UEI.SmartControl( 7297): --- this system supports 32-bit or 64-bit only
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7297): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7297): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7297): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7297): --- Selecting new region: 2
,I/UEI.SmartControl( 7297): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7297): Platform has CIR...
D/UEI.SmartControl( 7297): NO CIR support, need to check package...
I/UEI.SmartControl( 7297): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7297): QS Service created
E/UEI.SmartControl( 7297): QS start get config
,D/UEI.SmartControl( 7297): Loading JNI Libs...
,D/UEI.SmartControl( 7297):  configuring local db...
D/UEI.SmartControl( 7297):  ---- Has DB8: true
,D/UEI.SmartControl( 7297): QS start statue = true Error code = 0
D/UEI.SmartControl( 7297): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7297): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7297): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7297): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7297): IrrcClient ++ 
D/irrcClient( 7297): getIrrcService ++ 
D/irrcClient( 7297): getIrrcService -- 
D/irrcClient( 7297): IrrcClient -- 
W/irrc_jni( 7297): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7297): Services init done
I/UEI.SmartControl( 7297): Device manager: loading config....
D/UEI.SmartControl( 7297): QS Service init finished
D/UEI.SmartControl( 7297): Config is loaded...
,D/UEI.SmartControl( 7297): QS Service version name: 0.1.73
D/UEI.SmartControl( 7297): QS Service version code: 1073
D/UEI.SmartControl( 7297): Service requested: Control
,D/UEI.SmartControl( 7297): Internal service binding...
D/UEI.SmartControl( 7297): -----IControl: 11
D/UEI.SmartControl( 7297): Caller: com.lge.qremote
D/UEI.SmartControl( 7297): ------------ IControl registerCallback...
I/UEI.SmartControl( 7297): Registering callback...
D/UEI.SmartControl( 7297): -----IControl: 19
D/UEI.SmartControl( 7297): Caller: com.lge.qremote
I/UEI.SmartControl( 7297): Registering Services Ready callback...
I/UEI.SmartControl( 7297): Notify client services are ready...
,D/UEI.SmartControl( 7297): -----IControl: 8
D/UEI.SmartControl( 7297): Caller: com.lge.qremote
I/AudioManager( 6943): getMode name:com.lge.qremote
I/AudioManager( 6943): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7297):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7297): Notify AllClients services are ready: 0
,I/AudioManager( 6943): getMode name:com.lge.qremote
I/Icing   ( 4268): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Icing   ( 4268): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  863): Killing 6839:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10038/pid_6839/cgroup.procs: No such file or directory
,D/PowerService( 1856): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1906): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1906): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
D/LEDHandler( 1856): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1856): Battery Level Remaining: 100%
D/LEDHandler( 1856): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
,D/HeadsetStateMachine( 2060): Disconnected process message: 10, size: 0
D/charger_monitor(  480): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  863): battery changed pluggedType: 2
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  863): Killing 6556:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10061/pid_6556/cgroup.procs: No such file or directory
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7297): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 135191116516; DSPS: 4530011; Offset : -3064727093
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  863): ELAPSED_WAKEUP set : Alarm{182f1fe7 type 2 when 140187 com.google.android.gms} when 140187
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1453370568320 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  863): ALS enabled for SRE
,D/PowerManagerServiceEx(  863): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28388 ms ago)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdlights(  863): set_light_backlight: 252
,D/qdlights(  863): set_light_backlight: 249
D/qdlights(  863): set_light_backlight: 246
,D/qdlights(  863): set_light_backlight: 242
,D/qdlights(  863): set_light_backlight: 239
,D/qdlights(  863): set_light_backlight: 236
,D/qdlights(  863): set_light_backlight: 232
,D/qdlights(  863): set_light_backlight: 229
,D/qdlights(  863): set_light_backlight: 226
,D/qdlights(  863): set_light_backlight: 222
,D/qdlights(  863): set_light_backlight: 219
,D/qdlights(  863): set_light_backlight: 216
,D/qdlights(  863): set_light_backlight: 212
,D/qdlights(  863): set_light_backlight: 209
,D/qdlights(  863): set_light_backlight: 206
,D/qdlights(  863): set_light_backlight: 202
,D/qdlights(  863): set_light_backlight: 199
,D/qdlights(  863): set_light_backlight: 196
,D/qdlights(  863): set_light_backlight: 192
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
D/qdlights(  863): set_light_backlight: 189
,D/qdlights(  863): set_light_backlight: 186
,D/qdlights(  863): set_light_backlight: 182
,D/qdlights(  863): set_light_backlight: 179
,D/qdlights(  863): set_light_backlight: 176
,D/qdlights(  863): set_light_backlight: 172
,D/qdlights(  863): set_light_backlight: 169
,D/qdlights(  863): set_light_backlight: 166
,D/qdlights(  863): set_light_backlight: 162
,D/qdlights(  863): set_light_backlight: 159
,D/qdlights(  863): set_light_backlight: 156
,D/qdlights(  863): set_light_backlight: 152
,D/qdlights(  863): set_light_backlight: 149
,D/qdlights(  863): set_light_backlight: 146
,D/qdlights(  863): set_light_backlight: 142
,D/qdlights(  863): set_light_backlight: 139
,D/qdlights(  863): set_light_backlight: 136
,D/qdlights(  863): set_light_backlight: 132
,D/qdlights(  863): set_light_backlight: 129
,D/qdlights(  863): set_light_backlight: 126
,D/qdlights(  863): set_light_backlight: 122
,D/qdlights(  863): set_light_backlight: 119
,D/qdlights(  863): set_light_backlight: 116
,D/qdlights(  863): set_light_backlight: 112
,D/qdlights(  863): set_light_backlight: 109
,D/qdlights(  863): set_light_backlight: 106
,D/qdlights(  863): set_light_backlight: 102
,D/qdlights(  863): set_light_backlight: 99
,D/qdlights(  863): set_light_backlight: 96
,D/qdlights(  863): set_light_backlight: 92
,D/qdlights(  863): set_light_backlight: 89
,D/qdlights(  863): set_light_backlight: 86
,D/qdlights(  863): set_light_backlight: 82
,D/qdlights(  863): set_light_backlight: 79
,D/qdlights(  863): set_light_backlight: 76
,D/qdlights(  863): set_light_backlight: 72
,D/qdlights(  863): set_light_backlight: 69
,D/qdlights(  863): set_light_backlight: 66
,D/qdlights(  863): set_light_backlight: 62
,D/qdlights(  863): set_light_backlight: 59
,D/qdlights(  863): set_light_backlight: 56
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  863): set_light_backlight: 52
,D/qdlights(  863): set_light_backlight: 49
,D/qdlights(  863): set_light_backlight: 46
,D/qdlights(  863): set_light_backlight: 42
,D/qdlights(  863): set_light_backlight: 39
,D/qdlights(  863): set_light_backlight: 36
,D/qdlights(  863): set_light_backlight: 32
,D/qdlights(  863): set_light_backlight: 29
,D/qdlights(  863): set_light_backlight: 26
,D/qdlights(  863): set_light_backlight: 22
,D/qdlights(  863): set_light_backlight: 19
,D/qdlights(  863): set_light_backlight: 16
,D/qdlights(  863): set_light_backlight: 12
,D/qdlights(  863): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PowerManagerServiceEx(  863): acquireWakeLockInternal: lock=510213694, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=863
,D/WeatherService( 2844): 2 : TimeTick Intent has been received, Time(hour:min:sec) 11:3:0
,D/WeatherService( 2844): 2 : TimeTick Intent And Screen On
D/WeatherService( 2844): 2 : SDK version : 21
W/ActivityManager(  863): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2844): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2844): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2844): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2844): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2844): 2 : This is isUpdating : false
D/WeatherService( 2844): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2844): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2844): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2844): 2 : Fixed theme : optimus
I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
,D/WeatherReflect( 2844): 2 : Map key string is -2
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
,I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/lim     ( 2844): 2 : time = 11:03
,I/WeatherReflect( 2844): Model Name : LG-D722
D/WeatherTheme( 2844): 2 : Different view - status_min_formatted : 02 != 03
D/WeatherTheme( 2844): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2844): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2844): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2844): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2844): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2844): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2844): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2844): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2844): forecast size is 0
D/Theme   ( 2844): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2844): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2844): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2844): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2844): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2844): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2844): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2844): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2844): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2844): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2844): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2844): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2844): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2844): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2844): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2844): url is : null
D/Theme   ( 2844): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2844): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2844): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2844): 2 : update view, appWidgetId: 2
D/WeatherService( 2844): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 11:3:0
D/PowerManagerServiceEx(  863): releaseWakeLockInternal: lock=510213694 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1950): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
E/[LgeWidgetLib]LgeAppWidgetHostView( 1950): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 155191788175; DSPS: 5185393; Offset : -3064727133
,I/PowerManagerService(  863): ALS enabled for SRE
D/PowerManagerServiceEx(  863): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35377 ms ago)
I/PowerManagerService(  863): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  863): ALS enabled for SRE
D/PowerManagerServiceEx(  863): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35386 ms ago)
W/ContextImpl(  863): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  863): Sleeping (uid 1000)...
D/LPWGController(  863): [updateScreenState] screen on = false
D/LPWGController(  863): disable proximity sensor
D/LPWGController(  863): enable proximity sensor
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/SensorManager(  863): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1d33d52c] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  863): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  863): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  863): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  863): activate: handle is 48, enable
V/sensors_hal_Ctx(  863): activate sensors is 1400000000000
D/sensors_hal_Thresh(  863): enable: handle=48
I/sensors_hal_SAM(  863): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  863): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  863): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  863): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  863): enable: Received response: 0
D/PowerManagerServiceEx(  863): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35451 ms ago)
I/Adreno-EGL(  863): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  863): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  863): Build Date: 03/02/15 Mon
I/Adreno-EGL(  863): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  863): Remote Branch: 
I/Adreno-EGL(  863): Local Patches: 
I/Adreno-EGL(  863): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1056 us)
,I/Sensors (  428): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  863): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  863): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  863): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  863): processInd: handle 48, count=1
V/sensors_hal_Thresh(  863): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  863): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  863): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  863): poll: count: 256
I/sensors_hal_Ctx(  863): poll: released wakelock sensor_ind
D/sensors_hal_Util(  863): waitForResponse: timeout=0
D/LPWGController(  863): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  863): current mode = 1  value = 1 1
I/LPWGController(  863): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  863): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  863): set_light_backlight: 0
,I/SensorManager(  863): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  863): activate: handle is 46, disable
V/sensors_hal_Ctx(  863): activate sensors is 1000000000000
D/sensors_hal_LP2(  863): enable: handle=46
D/sensors_hal_LP2(  863): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  863): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  863): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/sensors_hal_SAM(  863): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  863): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  863): Display changed displayId=0
,D/DSDPConnection( 1769): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  863): Excessive delay in setPowerMode(): 196ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  863): Got set_interactive hint
D/KeyguardViewMediator( 1369): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1369): notifyScreenOffLocked
D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1369): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1369): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1369): unregisterProximitySensor
,D/WifiServerServiceExt(  863): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1369): onScreenTurnedOff why = 3
,I/WifiServerServiceExt(  863): set CMD_KT_SCAN_INTERVAL
V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 863
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=on
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
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_ON
D/GpsLocationProvider(  863): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/SplitWindow(  863): check instance of lgWin Window{33b22ffb u0 SearchPanel}
,I/QCNEJ   ( 1906): |CORE| sendScreenState: state:true
D/InputDispatcher(  863): Window went away: Window{184615e1 u0 SearchPanel}
,I/[SystemUI]Clock( 1369): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1369): time changed, timezoneChanged : false
,I/LEDService( 1856): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1856): stopPatternFlashing()
I/Cliptray Service( 1856): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1856): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1856): lockStatus = 0
I/LEDService( 1856): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1856): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1825): action : android.intent.action.SCREEN_ON
I/LEDService( 1856): updateLightsLocked : turn off led
D/qdlights( 1856): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1856): RESTART MSG
D/NfcServiceNXP( 1825): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1825): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1825): isRequireNfcCRouting() return true
D/LNfcService( 1825): isHCERoutingtoHost() return : true
D/NfcService( 1825): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1825): mEnableLPD: true
D/NfcService( 1825): mEnableReader: false
D/NfcService( 1825): mEnableHostRouting: true
D/NfcService( 1825): newParams.techmask= mTechMask: default
D/NfcService( 1825): mEnableLPD: true
D/NfcService( 1825): mEnableReader: false
D/NfcService( 1825): mEnableHostRouting: true
D/NfcService( 1825): screenState= 3
D/NfcService( 1825): Discovery configuration equal, not updating.
D/Ulp_jni (  863): JNI:system_update. Event-0
,V/PhoneApp( 1769): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): ACTION_SCREEN_ON
,D/WeatherService( 2844): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:3:4
D/WeatherService( 2844): 2 : ACTION screen on
D/WeatherService( 2844): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2844): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherService( 2844): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:3:4
D/AppCleanupService( 4084): android.intent.action.SCREEN_ON
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 863
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
,D/WifiController(  863): CMD_SCREEN_OFF 
D/WifiController(  863): shouldWifiStayAwake TRUE
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_OFF
D/GpsLocationProvider(  863): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1906): |CORE| sendScreenState: state:false
I/LEDService( 1856): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1856): stopPatternFlashing()
D/qdlights( 1856): set_light_notifications: 0,0,0,0,3
I/LEDService( 1856): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1856): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1856): clear
I/Cliptray Service( 1856): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1856): updateLightsLocked : turn on led
D/LNfcService( 1825): action : android.intent.action.SCREEN_OFF
E/LEDService( 1856): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1856): Can't handle this request of patternId:0
D/LEDHandler( 1856): RESTART MSG
D/NfcServiceNXP( 1825): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1950): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1769): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): ACTION_SCREEN_OFF
D/WeatherService( 2844): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:3:4
D/WeatherService( 2844): 2 : ACTION screen off
D/WeatherService( 2844): 2 : TimeTick Receiver Unregister
D/WeatherService( 2844): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:3:4
,D/AppCleanupService( 4084): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4084): AppUsageStatsSaveTask
E/NxpNfcJni( 1825): getReconnectState = 0x0
,D/LCardEmulationManager( 1825): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1825): getDefaultRoute
D/LNfcService( 1825): isRequireNfcCRouting() return true
D/LNfcService( 1825): isHCERoutingtoHost() return : true
D/NfcService( 1825): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1825): mEnableLPD: true
D/NfcService( 1825): mEnableReader: false
D/NfcService( 1825): mEnableHostRouting: true
D/NfcService( 1825): newParams.techmask= mTechMask: 0
D/NfcService( 1825): mEnableLPD: true
D/NfcService( 1825): mEnableReader: false
D/NfcService( 1825): mEnableHostRouting: true
D/NfcService( 1825): screenState= 1
E/NxpNfcJni( 1825): getReconnectState = 0x0
,I/Sensors (  428): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1369): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  863): ELAPSED_WAKEUP set : Alarm{249f1818 type 2 when 161334 com.android.systemui} when 161334
,D/PhoneUtils( 1769): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1769): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1769): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1769): getCallState : 0
,D/PhoneUtils( 1769): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1769): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1769): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1369): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1369): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 175192542543; DSPS: 5840778; Offset : -3064735547
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  863): ELAPSED_WAKEUP set : Alarm{ba4c271 type 2 when 186876 com.google.android.gms} when 186876
,I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 63 seconds from now (1453370615082)
,D/GetConfigurationSnapshotOperation( 1733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1856): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  480): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1906): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/QCNEJ   ( 1906): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1856): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1856): Battery Level Remaining: 100%
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LEDHandler( 1856): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  863): battery changed pluggedType: 2
D/HeadsetStateMachine( 2060): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 43441(2MB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 13MB/22MB, paused 1.563ms total 109.697ms
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/art     (  863): Explicit concurrent mark sweep GC freed 50938(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.656ms total 164.190ms
,V/AlarmManager(  863): ELAPSED_WAKEUP set : Alarm{eda29e1 type 2 when 190219 android} when 190219
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 195193223629; DSPS: 6496160; Offset : -3064726291
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 215193978360; DSPS: 7151545; Offset : -3064734083
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 235194742259; DSPS: 7806930; Offset : -3064733852
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  480): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1856): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/HeadsetStateMachine( 2060): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1906): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1906): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1856): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1856): Battery Level Remaining: 100%
D/LEDHandler( 1856): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  863): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 255195423085; DSPS: 8462313; Offset : -3064754123
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 275196183338; DSPS: 9117697; Offset : -3064726318
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 295196939632; DSPS: 9773082; Offset : -3064733303
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  480): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1856): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1856): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/charger_monitor(  480): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  480): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1856): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/HeadsetStateMachine( 2060): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1906): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1906): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1856): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1856): Battery Level Remaining: 100%
D/LEDHandler( 1856): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  863): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  480): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1856): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 315197621655; DSPS: 10428465; Offset : -3064753575
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6059): --= Surplus to requirements =--
I/jxcore-log( 6059): 
I/jxcore-log( 6059): ****TEST TOOK:  ms ****
I/jxcore-log( 6059): 
I/jxcore-log( 6059): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6059): 
,D/AndroidRuntime( 7490): 
D/AndroidRuntime( 7490): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7490): CheckJNI is OFF
,D/AndroidRuntime( 7490): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  863): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  863): Killing 6059:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  863): WIN DEATH: Window{65a45d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  863): Focus left window: Window{65a45d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  863): Window went away: Window{65a45d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  863): Skipping PackageSetting{1847e1e5 com.example.hello/10317} due to missing metadata
,I/ActivityManager(  863):   Force finishing activity ActivityRecord{ad67572 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  863): Display changed displayId=0
D/DSDPConnection( 1769): Display #0 changed.
,W/ActivityManager(  863): Spurious death for ProcessRecord{10ac9306 6059:com.test.thalitest/u0a316}, curProc for 6059: null
,I/ActivityManager(  863): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,I/[LGHome]EVENT( 1950): [Launcher.java:5203:onStart()]onStart
I/[LGHome]EVENT( 1950): [Launcher.java:776:onResume()]onResume
,D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  863): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1906): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3601): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3601): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3601): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3601): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3601): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3601): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3601): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3601): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3601): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3601): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3601): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3601): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 2034): Explicit concurrent mark sweep GC freed 8967(579KB) AllocSpace objects, 4(95KB) LOS objects, 40% free, 12MB/20MB, paused 2.666ms total 100.403ms
,I/ActivityManager(  863): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7520 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1950): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1950): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 21.292ms
I/art     ( 4268): Explicit concurrent mark sweep GC freed 19922(1165KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 14MB/18MB, paused 813us total 140.059ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 329us total 20.737ms
,I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1950): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1950): [Launcher.java:929:onResume()]onResume end
I/Activity( 1950): Activity.onPostResume() called 
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.140ms
D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
,I/[LGHome]EVENT( 1950): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
,W/[LGHome]LGWallpaperInfo( 1950): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1950): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
I/SystemUI[Framework](  863): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,D/InputDispatcher(  863): Focus entered window: Window{1888eced u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  863): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  863): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  863): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  863): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3eeee134,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  863): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  863): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  863): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  863): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  863): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  863): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3eeee134,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  863): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/KeyguardModel( 1369): handleShortcutListChanged...
I/[LGHome]EVENT( 1950): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1950): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1950): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
I/[LGHome]EVENT( 1950): [Launcher.java:5214:onStop()]onStop
,D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
I/[LGHome]EVENT( 1950): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1950): [setNavigationBarColor] color=0x 0
,W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/art     (  863): Explicit concurrent mark sweep GC freed 12495(955KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.707ms total 226.972ms
I/art     (  863): WaitForGcToComplete blocked for 116.739ms for cause Explicit
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
,W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourcesManager( 7520): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7520): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7520): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1369): handleShortcutListChanged...
D/administrator(  863): Handling package changes for user 0
,W/InputMethodManagerService(  863): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  863): Got RemoteException sending setActive(false) notification to pid 6059 uid 10316
,I/[LGHome]Launcher.Model( 1950): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/LGEmail ( 7520): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/art     (  863): Explicit concurrent mark sweep GC freed 4248(242KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 20.283ms total 308.202ms
I/Timeline(  863): Timeline: Activity_windows_visible id: ActivityRecord{2ad76c0a u0 com.lge.launcher2/.Launcher t221} time:323593
,W/IInputConnectionWrapper( 1950): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1950): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1625): Unable to connect to the editor to retrieve text... will retry later
,D/LGEmail ( 7520): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1950): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1950): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1950): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1950): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
,W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
D/LCardEmulationManager( 1825): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1825): getDefaultRoute
,W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,D/AndroidRuntime( 7490): Shutting down VM
I/NotificationService(  863): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  863): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  863): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/TaskPersister(  863): removeObsoleteFile: deleting file=222_task.xml
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1950): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/PackageChangeReceiver( 7520): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/AppUp4:PreloadHelper( 7126): added Exclude : com.test.thalitest
,W/ResourcesManager(  863): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  863): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7548 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
W/ResourceType(  863): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager(  863): Killing 7151:com.android.gallery3d/u0a23 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1950): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1950): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
W/libprocessgroup(  863): failed to open /acct/uid_10023/pid_7151/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1950): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 1950): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1950): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline( 1950): Timeline: Activity_idle id: android.os.BinderProxy@3ac72331 time:324135
,I/art     ( 1950): Explicit concurrent mark sweep GC freed 27318(1497KB) AllocSpace objects, 19(2MB) LOS objects, 40% free, 15MB/25MB, paused 777us total 55.830ms
,W/ResourcesManager( 7548): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
