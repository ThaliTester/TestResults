#### Test 58741471ee11130_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
D/PowerManagerServiceEx(  860): acquireWakeLockInternal: lock=290863082, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=860
--------- beginning of main
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/WeatherService( 2704): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:6:0
D/WeatherService( 2704): 2 : TimeTick Intent And Screen On
D/WeatherService( 2704): 2 : SDK version : 21
W/ActivityManager(  860): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2704): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2704): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2704): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2704): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2704): 2 : This is isUpdating : false
D/WeatherService( 2704): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2704): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2704): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2704): 2 : Fixed theme : optimus
D/WeatherReflect( 2704): 2 : Map key string is -2
D/lim     ( 2704): 2 : time = 14:06
I/WeatherReflect( 2704): Model Name : LG-D722
D/WeatherTheme( 2704): 2 : Different view - status_min_formatted : 05 != 06
D/WeatherTheme( 2704): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2704): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2704): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2704): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2704): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2704): forecast size is 0
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2704): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2704): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2704): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2704): url is : null
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2704): 2 : update view, appWidgetId: 2
D/WeatherService( 2704): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:6:0
D/PowerManagerServiceEx(  860): releaseWakeLockInternal: lock=290863082 [*alarm*], flags=0x0
I/GAv4-SVC( 5006): Google Analytics 8.4.89 is starting up.
I/GAV2    ( 5077): Thread[GAThread,5,main]: No campaign data found.
I/Icing   ( 5006): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/Icing   ( 5006): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
D/AndroidRuntime( 5415): 
D/AndroidRuntime( 5415): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5415): CheckJNI is OFF
D/AndroidRuntime( 5415): Calling main entry com.android.commands.am.Am
I/ActivityManager(  860): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  860): setTaskToReturnTo : TaskRecord{1e57e8b6 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  860): setTaskToReturnTo : TaskRecord{1e57e8b6 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  860): AppWindowTokenEx init.. 
D/ContextHelper(  860): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  860): Focus left window: Window{b43e01a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5415): Shutting down VM
D/SplitWindow(  860): check instance of lgWin Window{241e4f90 u0 Starting com.test.thalitest}
I/ActivityManager(  860): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5432 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  860): Starting window displayed
,I/SystemUI[Framework](  860): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  860): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  860): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  860): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  860): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@c67d9c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  860): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/BarTransitions( 1374): draw background and invalidate : color = a000000
D/BarTransitions( 1374): draw background and invalidate : color = a090909
I/HotwordDetector( 1942): Closing mic
,I/MicrophoneInputStream( 1942): mic_close com.google.android.apps.gsa.speech.audio.u@318c7113
V/AudioRecord( 1942): stop()
D/AudioRecord( 1942): AudioRecord->stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioFlinger(  279): Record stopped OK
V/AudioPolicyManager(  279): stopInput() input 16
V/AudioPolicyService(  279): AudioCommandThread() adding release patch delay 0
,V/AudioPolicyService(  279): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  279): ThreadBase::setParameters() routing=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb4393000
D/audio_hw_primary(  279): in_standby: enter: stream (0xb4036ac0) usecase(7: audio-record)
D/ContextHelper( 5432): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,V/audio_hw_primary(  279): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  279): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  279): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  279): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  279): disable_audio_route: exit
E/audio_hw_primary(  279): disable_snd_device: enter 144
D/hardware_info(  279): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  279): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  279): stop_input_stream: exit: status(0)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioFlinger(  279): RecordThread: loop stopping
,V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  279): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  279): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  279): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyService(  279): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  279): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  279): setParameters(): io 16, keyvalue hotword_active=0, calling pid 279
V/AudioFlinger(  279): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  279): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  279): in_set_parameters: exit: status(0)
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb4393000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioRecord( 1942): stop()
V/AudioRecord( 1942): stop()
V/AudioRecord( 1942): stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 16
V/AudioPolicyManager(  279): closeInput(16)
V/AudioFlinger(  279): closeInput() 16
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  860): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1942): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  279): ThreadBase::exit
V/AudioSystem( 1754): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 3107): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1972): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2723): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): releasing 15 from 1942 for -1
V/AudioFlinger(  279): RecordThread 0xb4393000 exiting
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb4036ac0)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb4036ac0) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioFlinger(  279): removeClient_l() pid 1942, calling pid 279
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
,I/HotwordRecognitionRnr( 1942): Hotword detection finished
I/HotwordRecognitionRnr( 1942): Stopping hotword detection.
I/WebViewFactory( 5432): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5432): Time to load native libraries: 2 ms (timestamps 332-334)
,I/LibraryLoader( 5432): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5432): Binding Chromium to main looper Looper (main, tid 1) {305c3764}
I/LibraryLoader( 5432): Expected native library version number "",actual native library version number ""
,I/chromium( 5432): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5432): Initializing chromium process, singleProcess=true
,W/art     ( 5432): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5432): ApplicationContext is null in ApplicationStatus
W/chromium( 5432): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5432): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5432): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5432): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5432): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5432): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5432): Remote Branch: 
I/Adreno-EGL( 5432): Local Patches: 
I/Adreno-EGL( 5432): Reconstruct Branch: 
V/AudioPolicyService(  279): registerClient() client 0xb57e7fa0, uid 10316
,D/BluetoothManagerService(  860): Message: 20
,D/BluetoothManagerService(  860): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@353957f2:true
D/BluetoothAdapterService(274163152)( 1972): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c253a6
,W/art     ( 5432): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5432): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5432): CordovaWebView is running on device made by: LGE
,W/art     ( 5432): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5432): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5432): Activity.onPostResume() called 
,D/OpenGLRenderer( 5432): Render dirty regions requested: true
I/OpenGLRenderer( 5432): Initialized EGL, version 1.4
D/OpenGLRenderer( 5432): Enabling debug mode 0
,D/Atlas   ( 5432): Validating map...
,D/SplitWindow(  860): check instance of lgWin Window{2ef3a1a2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5432): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/InputDispatcher(  860): Focus entered window: Window{2ef3a1a2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  860): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  860): Displayed com.test.thalitest/.MainActivity: +1s86ms
I/Timeline(  860): Timeline: Activity_windows_visible id: ActivityRecord{2719b9b7 u0 com.test.thalitest/.MainActivity t222} time:80925
I/Timeline( 5432): Timeline: Activity_idle id: android.os.BinderProxy@5e53583 time:80944
,W/BindingManager( 5432): Cannot call determinedVisibility() - never saw a connection for the pid: 5432
,D/JsMessageQueue( 5432): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  860): Killing 5263:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  860): failed to open /acct/uid_10011/pid_5263/cgroup.procs: No such file or directory
,I/ActivityManager(  860): Killing 5289:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  860): failed to open /acct/uid_10023/pid_5289/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 5229): Internal timer expired: 1
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{1b2bc2fa type 2 when 81687 com.google.android.gms} when 81687
,D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/jxcore_app_log( 5432): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618700800
,I/chromium( 5432): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 5432): CheckpointMarkThreadRoots callback created = 0x9a9a84a0
,I/art     ( 5432): CheckpointMarkThreadRoots callback created = 0x9a9a8470
,I/art     ( 5432): Background sticky concurrent mark sweep GC freed 33064(3MB) AllocSpace objects, 11(2MB) LOS objects, 24% free, 15MB/20MB, paused 7.130ms total 47.285ms
,D/InitAlarmsService( 3658): Clearing and rescheduling alarms.
,I/ActivityManager(  860): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5521 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,W/ResourcesManager( 5521): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5521): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@6792a1b
,D/CalendarProvider2( 5521): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5521): Created com.android.providers.calendar.CalendarAlarmManager@305c3764(com.android.providers.calendar.CalendarProvider2@6792a1b)
,D/CalendarProvider2( 5521): Scheduling check of next Alarm
D/CalendarProvider2( 5521): SCHEDULE_ALARM_REMOVE
I/ActivityManager(  860): Killing 3658:com.android.calendar/u0a13 (adj 15): empty #11
,I/art     ( 5432): Background sticky concurrent mark sweep GC freed 21848(1943KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 7.388ms total 31.452ms
,W/jxcore-log( 5432): Initializing JXcore engine
,W/jxcore-log( 5432): JXcore engine is ready
W/libprocessgroup(  860): failed to open /acct/uid_10013/pid_3658/cgroup.procs: No such file or directory
,W/Thread-632( 5513): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5899]" dev="sockfs" ino=5899 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-632( 5513): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-632( 5513): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8349]" dev="sockfs" ino=8349 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-632( 5513): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-632( 5513): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-632( 5513): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[23203]" dev="sockfs" ino=23203 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5432): Starting JXcore engine
,W/jxcore-log( 5432): Platform android
W/jxcore-log( 5432): 
W/jxcore-log( 5432): Process ARCH arm
W/jxcore-log( 5432): 
,I/jxcore-log( 5432): JXcore Cordova bridge is ready!
I/jxcore-log( 5432): 
,W/jxcore-log( 5432): JXcore engine is started
I/CalendarProvider2( 5521): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5521): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  860): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5549 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  860): Killing 5311:com.android.contacts/u0a18 (adj 15): empty #11
,I/jxcore-log( 5432): Toggling radios to true
I/jxcore-log( 5432): 
,D/BluetoothAdapter( 5432): enable(): BT is already enabled..!
W/libprocessgroup(  860): failed to open /acct/uid_10018/pid_5311/cgroup.procs: No such file or directory
,D/WifiServiceImplEx(  860): setWifiEnabled: true pid=5432, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  860): setWifiEnabled: true pid=5432, uid=10316
D/WifiServiceImplEx(  860): disconnect pid=5432, uid=10316, packageName=com.test.thalitest
W/ResourcesManager( 5549): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/WifiServiceImplEx(  860): reconnect pid=5432, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5432): Radios toggled
I/jxcore-log( 5432): 
I/jxcore-log( 5432): My device name is: LGE-LG-D722
I/jxcore-log( 5432): 
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 14:06:05.817 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiHS20(  860): hidePasspointNotification off =false
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 14:06:05.821 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 14:06:05.844 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  860): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  860): setSupplicantStateSCANNING
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/CalendarApplication( 5549): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 5549): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 5549): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@39f89991, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@4c9c0f6, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@36f64cf7, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@305c3764, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2b7c3dcd, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3848f682, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1cb8c193, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@105765d0, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@251be9c9, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2893f8ce, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1a23e3ef, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@a950efc, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3ef05985, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@97ad3da, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2a74d00b, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1ea21ee8, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3fe20901, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@9c253a6, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@359e61e7, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@35ee4194, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1ae5343d, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2db00432, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@5e53583, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3f37e300, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@3f5d739, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@656317e, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3b3ba6df, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@14b82f2c, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@18d3adf5, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@119fe78a, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@185dd1fb, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@190f1218, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@197e3471, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@f1cf256, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@5ad92d7, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@36ef37c4, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2c70a6ad, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@158ddde2, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@25ce8573, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2f8a0c30, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@2a9e00a9, lg_preferences_rece,nt_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@352ff62
D/GeneralPreferenceUtils( 5549): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,D/Config  ( 5549): [init]
I/Config  ( 5549): LGCalendar ver.4.40.17
I/Config  ( 5549): start check model
I/Config  ( 5549): start check native_ca
I/Config  ( 5549): Config Operator=OPEN, Country=EU
D/Config  ( 5549): [setDefaultValuesToPref]
D/Config  ( 5549): [parseProfiles]
D/ProfilesParser( 5549): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5549): [debug_displayParseInfos] profile.operator = null
,D/Config  ( 5549): [updateProfiletoCountryInfo]
D/GeneralPreference( 5549): [checkAndMigrateOldPreference]
D/AlertReceiver( 5549): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 5549): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 5549): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 5549): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,W/HolidayIntentService( 5549): onHandleIntent
,D/HolidayDataLoader( 5549): readJsonAsset : holiday.json
D/AlertService( 5549): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/HolidayIntentService( 5549): onHandleIntent:holiday data empty
,I/art     (  860): Explicit concurrent mark sweep GC freed 19885(995KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.176ms total 154.808ms
,I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,E/AgendaWidgetManager( 5549): [updateWidgets] 
D/MonthWidgetProvider( 5549): [onReceive]
D/CalendarWidgetProvider( 5549): [onReceive]
D/CalendarWidgetProvider( 5549): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
D/CalendarTypeController( 5549): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 5549): [onReceive]
D/CalendarWidgetProvider( 5549): [onReceive]
D/CalendarWidgetProvider( 5549): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
D/CalendarTypeController( 5549): [onCreate] mContext.getPackageName() = com.android.calendar
,I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5549): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5549): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/ActivityManager(  860): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5585 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/AlertUtils( 5549): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 5549): End InitializeAlertRingtoneService.onHandleIntent
,W/ResourcesManager( 5585): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5585): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5585): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5585): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5585): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 5585): Using schema version: 115
,I/IndexDatabaseHelper( 5585): Index is fine
V/WiFiOffLoadBroadcast( 5585): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5585): MCCMNC not supported: null
,I/ActivityManager(  860): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5608 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  860): Killing 5330:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  860): failed to open /acct/uid_10069/pid_5330/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 5585): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5585): MCCMNC not supported: null
I/PCSuite ( 5608): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5608): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5608): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 5585): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5585): MCCMNC not supported: null
I/ActivityManager(  860): Killing 5347:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  860): failed to open /acct/uid_10086/pid_5347/cgroup.procs: No such file or directory
,V/AlarmManager(  860): RTC_WAKEUP set : Alarm{2aa9494c type 0 when 1455023168036 com.android.vending} when 1455023168036
,D/Finsky  ( 4930): [565] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4930): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  860): Process com.google.android.gms (pid 5006) has died
W/ActivityManager(  860): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{3b318d95 type 2 when 88244 com.android.providers.calendar} when 88244
,D/CalendarProviderBroadcastReceiver( 5521): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5521): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5521): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 5521): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5521): [getOrCreateCalendarAlarmManager]
,D/CalendarProvider2( 5521): [IntentService] Release Lock
D/CalendarProvider2( 5521): CalendarProviderIntentService.onDestroy()
,I/ActivityManager(  860): Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=5636 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 5636): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5636): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5636): VM with version 2.1.0 has multidex support
,I/MultiDex( 5636): install
I/MultiDex( 5636): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  860): Process com.google.android.gm (pid 5077) has died
,V/JNIHelp ( 5636): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/ActivityThread( 5636): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5636): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ef017bc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5636): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5636): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5636): com.google.android.gms: cancel(39789) by com.google.android.gms
I/GAv4-SVC( 5636): Google Analytics 8.4.89 is starting up.
,D/WearableService( 1736): callingUid 10006, callindPid: 1736
,E/MDM     ( 1736): [103] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5636): Restart initialization of location
,D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1736): com.google.android.gms: cancel(0) by com.google.android.gms
V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{2563ce49 type 2 when 89333 com.google.android.gms} when 89333
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/NativeLibraryUtils( 5636): Install completed successfully. count=14 extracted=0
,I/art     ( 5636): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5636): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5636): CheckpointMarkThreadRoots callback created = 0xb042dab0
,I/art     ( 5636): CheckpointMarkThreadRoots callback created = 0xb042daa0
,W/IcingInternalCorpora( 5636): getNumBytesRead when not calculated.
,I/art     ( 5636): Background partial concurrent mark sweep GC freed 4671(467KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 10MB/18MB, paused 7.790ms total 91.097ms
,W/GCoreFlp( 1736): No location to return for getLastLocation()
W/FusedLocationProvider( 1736): location=null
,D/AlertService( 5549): Beginning updateAlertNotification
,D/AlertService( 5549): No fired or scheduled alerts
I/NotificationManager( 5549): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(12) by com.android.calendar
,I/NotificationManager( 5549): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5549): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5549): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5549): No events found starting within 1 week.
,I/NotificationManager( 1942): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/AlarmManager(  860): RTC_WAKEUP set : Alarm{a042014 type 0 when 1455023172796 com.android.vending} when 1455023172796
,D/Finsky  ( 4930): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  860): android: cancelAsUser(2) by android
,D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 4930): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  860): android: cancelAsUser(2) by android
I/jxcore-log( 5432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5432): 
D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  860): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5716 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  860): android: cancelAsUser(2) by android
,D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 4930): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ResourcesManager( 5716): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5716): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5716): VM with version 2.1.0 has multidex support
I/MultiDex( 5716): install
,I/MultiDex( 5716): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5716): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5716): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5716): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@27749d06: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5716): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5716): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5716): com.google.android.gms: cancel(39789) by com.google.android.gms
E/MDM     ( 1736): [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5636): Restart initialization of location
D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ChimeraCfgMgr( 5716): Reading stored module config
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1736): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1736): No location to return for getLastLocation()
,W/FusedLocationProvider( 1736): location=null
D/ChimeraCfgMgr( 5716): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/NativeLibraryUtils( 5716): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 5716): Connecting to CarCallService...
,I/art     ( 5716): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5716): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 5716): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5716): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5716): Creating a new PhoneAdapter instance
W/ActivityManager(  860): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5716): setListener: com.google.android.gms.car.dn@380aff8d
W/ActivityManager(  860): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5716): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5716): Starting CarCallService with initial phone null
,I/NotificationManager( 5716): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 5716): Package validated; name: com.android.vending
,I/NotificationManager( 4930): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 4930): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/art     (  860): Explicit concurrent mark sweep GC freed 17593(800KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.542ms total 141.472ms
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  860): android: cancelAsUser(2) by android
,D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4930): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 4930): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  860): RTC_WAKEUP set : Alarm{1970dd1a type 0 when 1455023174245 com.android.vending} when 1455023174245
D/Finsky  ( 4930): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1736): client connected with version: 8296000
,D/Finsky  ( 4930): [574] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4930): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4930): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/NotificationManager(  860): android: cancelAsUser(2) by android
,D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,I/art     ( 1736): Explicit concurrent mark sweep GC freed 32681(2MB) AllocSpace objects, 22(352KB) LOS objects, 40% free, 13MB/22MB, paused 1.457ms total 94.953ms
,I/jxcore-log( 5432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5432): 
,I/jxcore-log( 5432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5432): 
,I/jxcore-log( 5432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5432): 
I/jxcore-log( 5432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5432): 
,I/jxcore-log( 5432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5432): 
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 94548355958; DSPS: 3196068; Offset : -3000891995
,I/ActivityManager(  860): Killing 5549:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  860): failed to open /acct/uid_10013/pid_5549/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 5716): mConnectedToCar = false, abort
,E/ActivityThread( 5716): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@39734ad5 that was originally bound here
E/ActivityThread( 5716): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@39734ad5 that was originally bound here
E/ActivityThread( 5716): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5716): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5716): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5716): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5716): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5716): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5716): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5716): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5716): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5716): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5716): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5716): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5716): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5716): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5716): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5716): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5716): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5716): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5716): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5716): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 5716): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3449e824 that was originally bound here
E/ActivityThread( 5716): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3449e824 that was originally bound here
E/ActivityThread( 5716): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5716): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5716): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5716): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5716): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5716): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5716): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5716): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5716): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5716): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5716): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5716): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5716): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5716): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 5716): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5716): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5716): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5716): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5716): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  860): Unbind failed: could not find connection for android.os.BinderProxy@86e6dc3
I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,I/jxcore-log( 5432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5432): 
,I/jxcore-log( 5432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5432): 
,I/jxcore-log( 5432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5432): 
,I/jxcore-log( 5432): Test app app.js loaded
I/jxcore-log( 5432): 
,I/chromium( 5432): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5432): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5432): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5432): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5432): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5432): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5432): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5432): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5432): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5432): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5432): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c76006 added. We now have 1 listener(s)
D/BluetoothAdapterService(274163152)( 1972): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c253a6
I/jxcore-log( 5432): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5432): 
I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  273): 
I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{24485640 type 2 when 104608 com.google.android.gms} when 104608
,D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,V/AlarmManager(  860): RTC_WAKEUP set : Alarm{de9f6be type 0 when 1455023188896 com.android.vending} when 1455023188896
,W/ContextImpl( 3440): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 4930): [565] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4930): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,I/MusicWidget( 2665): mDelayedStopHandler : unbind
,I/MusicBrowser( 2723): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2723): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2723): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2723): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2723): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2723): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2723): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2723): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  860):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2db00432com.lge.music.MediaPlaybackService$6@5e53583
,D/MusicBrowser( 2723): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@251be9c9
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2723): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2723): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2723): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2723): reset
V/MediaPlayer[Native]( 2723): setListener
,V/MediaPlayer[Native]( 2723): disconnect
V/MediaPlayer[Native]( 2723): destructor
V/AudioFlinger(  279): releasing 18 from 2723 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/MediaPlayer[Native]( 2723): disconnect
D/MusicBrowser( 2723): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2723): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2723): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2723): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2723): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2723): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2723): [SmartShareManagerClient] unregisterListener: 1060627200
W/SmartShareClient( 2723): [SmartShareManagerClient] unregisterListener invalid listener: 1060627200
I/SmartShareClient( 2723): [SmartShareManagerClient] terminate service: 2723/MediaPlaybackService/922111223
E/HomeCloudIF( 2723): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2723): [SmartShareManagerClient] unbindService context:android.app.Application@3f5d739
V/CloudHub( 2723): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2723): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2723): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2723): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2723): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  860): Killing 5585:com.android.settings/1000 (adj 15): empty #11
I/CloudHub( 2723): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29972
,W/libprocessgroup(  860): failed to open /acct/uid_1000/pid_5585/cgroup.procs: No such file or directory
D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 114549094335; DSPS: 3851452; Offset : -3000887446
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,I/CloudHub( 2723): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19972
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
D/charger_monitor(  484): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 134549758598; DSPS: 4506834; Offset : -3000892747
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{ac0231f type 2 when 135152 com.google.android.gms} when 135152
,D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,D/PowerManagerServiceEx(  860): acquireWakeLockInternal: lock=290863082, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=860
,D/WeatherService( 2704): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:7:0
D/WeatherService( 2704): 2 : TimeTick Intent And Screen On
D/WeatherService( 2704): 2 : SDK version : 21
W/ActivityManager(  860): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2704): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2704): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2704): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2704): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2704): 2 : This is isUpdating : false
D/WeatherService( 2704): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2704): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2704): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2704): 2 : Fixed theme : optimus
D/WeatherReflect( 2704): 2 : Map key string is -2
,D/lim     ( 2704): 2 : time = 14:07
I/WeatherReflect( 2704): Model Name : LG-D722
D/WeatherTheme( 2704): 2 : Different view - status_min_formatted : 06 != 07
D/WeatherTheme( 2704): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2704): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2704): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
,I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/Weather4x2_optimus( 2704): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2704): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2704): forecast size is 0
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2704): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2704): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2704): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2704): url is : null
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2704): 2 : update view, appWidgetId: 2
D/WeatherService( 2704): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:7:0
,D/PowerManagerServiceEx(  860): releaseWakeLockInternal: lock=290863082 [*alarm*], flags=0x0
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,I/CloudHub( 2723): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2723): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/PowerManagerService(  860): ALS enabled for SRE
D/PowerManagerServiceEx(  860): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27912 ms ago)
,D/qdlights(  860): set_light_backlight: 252
,D/qdlights(  860): set_light_backlight: 249
,D/qdlights(  860): set_light_backlight: 246
,D/qdlights(  860): set_light_backlight: 242
,D/qdlights(  860): set_light_backlight: 239
,D/qdlights(  860): set_light_backlight: 236
,D/qdlights(  860): set_light_backlight: 232
,D/qdlights(  860): set_light_backlight: 229
,D/qdlights(  860): set_light_backlight: 226
,D/qdlights(  860): set_light_backlight: 222
,D/qdlights(  860): set_light_backlight: 219
,D/qdlights(  860): set_light_backlight: 216
,D/qdlights(  860): set_light_backlight: 212
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
D/qdlights(  860): set_light_backlight: 209
,D/qdlights(  860): set_light_backlight: 206
,D/qdlights(  860): set_light_backlight: 202
,D/qdlights(  860): set_light_backlight: 199
,D/qdlights(  860): set_light_backlight: 196
,D/qdlights(  860): set_light_backlight: 192
,D/qdlights(  860): set_light_backlight: 189
,D/qdlights(  860): set_light_backlight: 186
,D/qdlights(  860): set_light_backlight: 182
,D/qdlights(  860): set_light_backlight: 179
,D/qdlights(  860): set_light_backlight: 176
,D/qdlights(  860): set_light_backlight: 172
,D/qdlights(  860): set_light_backlight: 169
,D/qdlights(  860): set_light_backlight: 166
,D/qdlights(  860): set_light_backlight: 162
,D/qdlights(  860): set_light_backlight: 159
,D/qdlights(  860): set_light_backlight: 156
,D/qdlights(  860): set_light_backlight: 152
,D/qdlights(  860): set_light_backlight: 149
,D/qdlights(  860): set_light_backlight: 146
,D/qdlights(  860): set_light_backlight: 142
,D/qdlights(  860): set_light_backlight: 139
,D/qdlights(  860): set_light_backlight: 136
,D/qdlights(  860): set_light_backlight: 132
,D/qdlights(  860): set_light_backlight: 129
,D/qdlights(  860): set_light_backlight: 126
,D/qdlights(  860): set_light_backlight: 122
,D/qdlights(  860): set_light_backlight: 119
,D/qdlights(  860): set_light_backlight: 116
,D/qdlights(  860): set_light_backlight: 112
,D/qdlights(  860): set_light_backlight: 109
,D/qdlights(  860): set_light_backlight: 106
,D/qdlights(  860): set_light_backlight: 102
,D/qdlights(  860): set_light_backlight: 99
,D/qdlights(  860): set_light_backlight: 96
,D/qdlights(  860): set_light_backlight: 92
,D/qdlights(  860): set_light_backlight: 89
,D/qdlights(  860): set_light_backlight: 86
,D/qdlights(  860): set_light_backlight: 82
,D/qdlights(  860): set_light_backlight: 79
,D/qdlights(  860): set_light_backlight: 76
,D/qdlights(  860): set_light_backlight: 72
,D/qdlights(  860): set_light_backlight: 69
,D/qdlights(  860): set_light_backlight: 66
,D/qdlights(  860): set_light_backlight: 62
,D/qdlights(  860): set_light_backlight: 59
,D/qdlights(  860): set_light_backlight: 56
,D/qdlights(  860): set_light_backlight: 52
,D/qdlights(  860): set_light_backlight: 49
,D/qdlights(  860): set_light_backlight: 46
,D/qdlights(  860): set_light_backlight: 42
,D/qdlights(  860): set_light_backlight: 39
,D/qdlights(  860): set_light_backlight: 36
,D/qdlights(  860): set_light_backlight: 32
,D/qdlights(  860): set_light_backlight: 29
,D/qdlights(  860): set_light_backlight: 26
,D/qdlights(  860): set_light_backlight: 22
,D/qdlights(  860): set_light_backlight: 19
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{277c966c type 2 when 134458 com.google.android.gms} when 134458
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/qdlights(  860): set_light_backlight: 16
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/qdlights(  860): set_light_backlight: 12
D/qdlights(  860): set_light_backlight: 10
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 154550313436; DSPS: 5162212; Offset : -3000887486
,I/PowerManagerService(  860): ALS enabled for SRE
D/PowerManagerServiceEx(  860): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34904 ms ago)
I/PowerManagerService(  860): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  860): ALS enabled for SRE
D/PowerManagerServiceEx(  860): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34917 ms ago)
,W/ContextImpl(  860): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  860): Sleeping (uid 1000)...
D/LPWGController(  860): [updateScreenState] screen on = false
D/LPWGController(  860): disable proximity sensor
D/LPWGController(  860): enable proximity sensor
I/SensorManager(  860): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@32d2ad58] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  860): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  860): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  860): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  860): activate: handle is 48, enable
V/sensors_hal_Ctx(  860): activate sensors is 1400000000000
D/sensors_hal_Thresh(  860): enable: handle=48
I/sensors_hal_SAM(  860): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  860): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  860): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  860): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  860): enable: Received response: 0
D/PowerManagerServiceEx(  860): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34971 ms ago)
I/Adreno-EGL(  860): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  860): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  860): Build Date: 03/02/15 Mon
I/Adreno-EGL(  860): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  860): Remote Branch: 
I/Adreno-EGL(  860): Local Patches: 
I/Adreno-EGL(  860): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (998 us)
,I/Sensors (  424): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  860): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  860): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  860): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  860): processInd: handle 48, count=1
V/sensors_hal_Thresh(  860): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  860): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  860): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  860): poll: count: 256
I/sensors_hal_Ctx(  860): poll: released wakelock sensor_ind
D/sensors_hal_Util(  860): waitForResponse: timeout=0
D/LPWGController(  860): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  860): current mode = 1  value = 1 1
I/LPWGController(  860): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  860): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  860): set_light_backlight: 0
,I/SensorManager(  860): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  860): activate: handle is 46, disable
,V/sensors_hal_Ctx(  860): activate sensors is 1000000000000
D/sensors_hal_LP2(  860): enable: handle=46
D/sensors_hal_LP2(  860): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  860): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  860): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  860): Display changed displayId=0
,V/sensors_hal_SAM(  860): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  860): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1754): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  860): Excessive delay in setPowerMode(): 226ms
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  860): Got set_interactive hint
D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1334): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1374): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1334): notifyScreenOffLocked
D/SmartCoverViewMediator( 1334): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1374): handleNotifyScreenOff
E/WifiNative-wlan0(  860): doBoolean: disable
,D/WifiServerServiceExt(  860): sendKtScanInterval  mRtspPlay : false
D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
,I/WifiServerServiceExt(  860): set CMD_KT_SCAN_INTERVAL
V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 860
D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=on
V/voice   (  279): voice_set_parameters: enter: screen_state=on
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
D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
,D/GpsLocationProvider(  860): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1841): |CORE| sendScreenState: state:true
I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1805): lockStatus = 0
I/LEDService( 1805): updateLightsLocked : turn off led
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1805): RESTART MSG
,D/SplitWindow(  860): check instance of lgWin Window{313d5717 u0 SearchPanel}
,D/LNfcService( 1788): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1788): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1788): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1788): isRequireNfcCRouting() return true
,D/LNfcService( 1788): isHCERoutingtoHost() return : true
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
D/InputDispatcher(  860): Window went away: Window{10cbfad7 u0 SearchPanel}
I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,D/Ulp_jni (  860): JNI:system_update. Event-0
,V/PhoneApp( 1754): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,I/ActivityManager(  860): Process com.lge.qremote (pid 5202) has died
D/UEI.SmartControl( 5229): Service.onUnbind: IControl
,D/UEI.SmartControl( 5229): Service.onDestroy
D/UEI.SmartControl( 5229): Shutdown IRRCPlayer... 
W/irrc_jni( 5229): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5229): ~IrrcClient ++ 
D/irrcClient( 5229): ~IrrcClient -- 
W/irrc_jni( 5229): IRRCPlayer_nativeFinalize -- 
,D/UEI.SmartControl( 5229): Blaster closed
D/UEI.SmartControl( 5229): Blaster closed
D/UEI.SmartControl( 5229): Shut down QS...
D/UEI.SmartControl( 5229): Stopped file observer...
,I/UEI.SmartControl( 5229): QS lib stop result = true
D/UEI.SmartControl( 5229): QS shutdown complete
D/WeatherService( 2704): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:7:17
D/WeatherService( 2704): 2 : ACTION screen on
D/WeatherService( 2704): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2704): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherService( 2704): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:7:17
,W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): ACTION_SCREEN_ON
D/AppCleanupService( 3941): android.intent.action.SCREEN_ON
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 860
,D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=off
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
E/WifiNative-wlan0(  860): doBoolean: disable
D/WifiController(  860): CMD_SCREEN_OFF 
D/WifiController(  860): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  860): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
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
,D/LNfcService( 1788): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1788): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1754): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2704): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:7:17
D/WeatherService( 2704): 2 : ACTION screen off
D/WeatherService( 2704): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2704): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:7:17
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): ACTION_SCREEN_OFF
D/AppCleanupService( 3941): android.intent.action.SCREEN_OFF
D/AppCleanupService( 3941): AppUsageStatsSaveTask
,E/NxpNfcJni( 1788): getReconnectState = 0x0
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
,I/Sensors (  424): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{1a714704 type 2 when 160882 com.android.systemui} when 160882
,D/PhoneUtils( 1754): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1754): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1754): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1754): getCallState : 0
,D/PhoneUtils( 1754): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1754): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1754): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 174557364417; DSPS: 5817803; Offset : -3000886170
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{36f6a4ed type 2 when 186579 com.google.android.gms} when 186579
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  860): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{9929f22 type 2 when 181559 android} when 181559
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{36364db3 type 2 when 193878 com.google.android.gms} when 193878
D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 194558053211; DSPS: 6473186; Offset : -3000899982
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{2c3dcf70 type 2 when 196237 com.google.android.gms} when 196237
,D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ClearcutLoggerApiImpl( 1736): disconnect managed GoogleApiClient
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 214558658464; DSPS: 7128566; Offset : -3000904301
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/PowerManagerServiceEx(  860): acquireWakeLockInternal: lock=290863082, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=860
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{c25a2e9 type 2 when 223887 com.google.android.gms} when 223887
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx(  860): releaseWakeLockInternal: lock=290863082 [*alarm*], flags=0x0
,I/VacuumService( 1736): Vacuum at: now=1455023312140 tag=VacuumService
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 234559261425; DSPS: 7783945; Offset : -3000881044
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 254559875844; DSPS: 8439326; Offset : -3000909343
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 274560590056; DSPS: 9094709; Offset : -3000895342
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 294561281194; DSPS: 9750092; Offset : -3000905457
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 314561957281; DSPS: 10405474; Offset : -3000901303
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/PowerManagerServiceEx(  860): acquireWakeLockInternal: lock=290863082, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=860
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{2d08729c type 2 when 318364 com.google.android.gms} when 318364
,D/PowerManagerServiceEx(  860): releaseWakeLockInternal: lock=290863082 [*alarm*], flags=0x0
,D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 334562651856; DSPS: 11060857; Offset : -3000908685
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/LocationManagerService(  860): remove 1bfc5ab2
,D/LocationManagerService(  860): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  860): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  860): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  860): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  860): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 354563256171; DSPS: 11716236; Offset : -3000883995
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  860): android: cancelAsUser(2) by android
,D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 374563940903; DSPS: 12371619; Offset : -3000901377
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 394564626885; DSPS: 13027001; Offset : -3000886729
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 414565222815; DSPS: 13682381; Offset : -3000901176
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 434565822130; DSPS: 14337760; Offset : -3000881565
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 454566426133; DSPS: 14993140; Offset : -3000888175
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
,D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 474567123730; DSPS: 15648523; Offset : -3000892820
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 494567732941; DSPS: 16303903; Offset : -3000893257
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 514568331214; DSPS: 16959283; Offset : -3000905570
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 534568933967; DSPS: 17614662; Offset : -3000882756
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 554569590834; DSPS: 18270044; Offset : -3000897406
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/PowerManagerServiceEx(  860): acquireWakeLockInternal: lock=290863082, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=860
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{1e6e09a3 type 2 when 562627 com.google.android.gms} when 562627
D/PowerManagerServiceEx(  860): releaseWakeLockInternal: lock=290863082 [*alarm*], flags=0x0
,D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 574570362389; DSPS: 18925429; Offset : -3000888608
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 594570957747; DSPS: 19580809; Offset : -3000903654
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  860): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 614571638051; DSPS: 20236191; Offset : -3000894606
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 634572236482; DSPS: 20891571; Offset : -3000906813
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  860): acquireWakeLockInternal: lock=290863082, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=860
,V/AlarmManager(  860): RTC_WAKEUP set : Alarm{12dbf4a0 type 0 when 1455023555355 com.google.android.gms} when 1455023555355
D/PowerManagerServiceEx(  860): releaseWakeLockInternal: lock=290863082 [*alarm*], flags=0x0
,I/NotificationManager( 5636): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/EventLogService( 5636): Aggregate from 1455021755267 (log), 1455021755267 (data)
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 654572900745; DSPS: 21546952; Offset : -3000883106
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  860): android: cancelAsUser(2) by android
,D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 674573578705; DSPS: 22202335; Offset : -3000906972
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 694574173073; DSPS: 22857714; Offset : -3000892282
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 714574856763; DSPS: 23513096; Offset : -3000880058
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 734575456286; DSPS: 24168476; Offset : -3000891094
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 754576136019; DSPS: 24823858; Offset : -3000884493
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 774576810073; DSPS: 25479241; Offset : -3000910624
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 794577426263; DSPS: 26134621; Offset : -3000904604
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 814578097766; DSPS: 26790003; Offset : -3000904514
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 834578698748; DSPS: 27445382; Offset : -3000883235
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 854579383272; DSPS: 28100765; Offset : -3000901058
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 874579982327; DSPS: 28756144; Offset : -3000881681
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 894580659976; DSPS: 29411527; Offset : -3000905676
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 914581263250; DSPS: 30066906; Offset : -3000882366
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 934581865690; DSPS: 30722286; Offset : -3000890304
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  860): acquireWakeLockInternal: lock=290863082, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=860
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{1ac4a193 type 2 when 949981 com.android.bluetooth} when 949981
D/PowerManagerServiceEx(  860): releaseWakeLockInternal: lock=290863082 [*alarm*], flags=0x0
,W/bt-smp  ( 1972): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1972): Plain text(LSB ~ MSB) = 32 1f 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 1972): Encrypted text(LSB ~ MSB) = f4 fd a4 bd 58 f4 d0 0a 49 05 78 c2 dc 38 ad 2b 
W/bt-btm  ( 1972): Stopping oneshot timer
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 954582496567; DSPS: 31377667; Offset : -3000900478
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  860): android: cancelAsUser(2) by android
,D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 974583178852; DSPS: 32033049; Offset : -3000889475
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 994583779885; DSPS: 32688429; Offset : -3000898586
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1014584405763; DSPS: 33343809; Offset : -3000883085
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1034585081589; DSPS: 33999192; Offset : -3000909397
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  860): acquireWakeLockInternal: lock=290863082, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=860
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{bf3b3a6 type 2 when 1051121 com.google.android.gms} when 1051121
D/PowerManagerServiceEx(  860): releaseWakeLockInternal: lock=290863082 [*alarm*], flags=0x0
,D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1054585689654; DSPS: 34654571; Offset : -3000880880
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1074586366157; DSPS: 35309954; Offset : -3000906595
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1094587043337; DSPS: 35965336; Offset : -3000900749
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1114587644631; DSPS: 36620716; Offset : -3000909573
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1134588331030; DSPS: 37276098; Offset : -3000894925
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1972): Disconnected process message: 10, size: 0
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1154588932897; DSPS: 37931478; Offset : -3000903200
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1174589688254; DSPS: 38586862; Offset : -3000880396
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1194590651060; DSPS: 39242254; Offset : -3000893918
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1214591248864; DSPS: 39897634; Offset : -3000906387
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/UsageStatsService(  860): User[0] Flushing usage stats to disk
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1234591892919; DSPS: 40553015; Offset : -3000903435
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1254592516870; DSPS: 41208395; Offset : -3000889680
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  860): android: cancelAsUser(2) by android
,D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  860): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 1274593141028; DSPS: 41863776; Offset : -3000906365
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6074): 
D/AndroidRuntime( 6074): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6074): CheckJNI is OFF
D/AndroidRuntime( 6074): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  860): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  860): Killing 5432:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  860): WIN DEATH: Window{2ef3a1a2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  860): Focus left window: Window{2ef3a1a2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  860): Window went away: Window{2ef3a1a2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  860): Skipping PackageSetting{10fe92d6 com.example.hello/10317} due to missing metadata
I/ActivityManager(  860):   Force finishing activity ActivityRecord{2719b9b7 u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  860): Display changed displayId=0
D/DSDPConnection( 1754): Display #0 changed.
W/ActivityManager(  860): Spurious death for ProcessRecord{30788df5 5432:com.test.thalitest/u0a316}, curProc for 5432: null
I/ActivityManager(  860): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1841): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
W/GeofencerStateMachine( 1736): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
W/System.err( 3440): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3440): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3440): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3440): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3440): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3440): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3440): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3440): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3440): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3440): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3440): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3440): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  860): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  860): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6104 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     ( 1942): Explicit concurrent mark sweep GC freed 1691(116KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 11MB/19MB, paused 1.712ms total 123.496ms
I/ActivityManager(  860): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6122 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
I/Activity( 1878): Activity.onPostResume() called 
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
I/art     (  860): Explicit concurrent mark sweep GC freed 50610(3MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 23MB/34MB, paused 8.992ms total 272.874ms
I/art     (  860): WaitForGcToComplete blocked for 245.109ms for cause Explicit
W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/LockScreenSettings( 6122): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/SystemUI[Framework](  860): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  860): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  860): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  860): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  860): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@c67d9c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  860): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  860): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/PhoneWindowManagerEx(  860): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  860): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  860): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  860): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@c67d9c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  860): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  860): Focus entered window: Window{b43e01a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/ResourcesManager( 6104): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourcesManager( 6104): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6104): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1374): handleShortcutListChanged...
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
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
D/KeyguardModel( 1374): handleShortcutListChanged...
W/InputMethodManagerService(  860): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  860): Got RemoteException sending setActive(false) notification to pid 5432 uid 10316
D/administrator(  860): Handling package changes for user 0
W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
I/Timeline( 1878): Timeline: Activity_idle id: android.os.BinderProxy@146e7ec time:1291868
I/Timeline(  860): Timeline: Activity_windows_visible id: ActivityRecord{d678ffa u0 com.lge.launcher2/.Launcher t221} time:1291886
E/b       ( 1620): Unable to connect to the editor to retrieve text... will retry later
I/art     ( 1878): Explicit concurrent mark sweep GC freed 8726(480KB) AllocSpace objects, 5(681KB) LOS objects, 39% free, 15MB/25MB, paused 1.526ms total 47.255ms
W/IInputConnectionWrapper( 1878): getTextAfterCursor on inactive InputConnection
I/art     (  860): Explicit concurrent mark sweep GC freed 8497(491KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.629ms total 293.546ms
I/LGEmail ( 6104): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/AndroidRuntime( 6074): Shutting down VM
D/LGEmail ( 6104): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
I/NotificationService(  860): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  860): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  860): Receieved: android.intent.action.PACKAGE_REMOVED
I/PackageChangeReceiver( 6104): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
W/ResourcesManager(  860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  860): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6153 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  860): Killing 5229:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  860): failed to open /acct/uid_10089/pid_5229/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  860): removeObsoleteFile: deleting file=222_task.xml
W/ResourceType(  860): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)

```
