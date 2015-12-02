#### Test 50388019193a02f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/[SMS_AD]( 3837): Intent action: android.intent.action.BOOT_COMPLETED
--------- beginning of system
W/libprocessgroup(  932): failed to open /acct/uid_10011/pid_3579/cgroup.procs: No such file or directory
I/InsertAccount( 3819): The account info in contact DB already exists
I/[SMS_AD]( 3837): Intent action: android.intent.action.BOOT_COMPLETED
I/ActivityManager(  932): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3857 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  932): Killing 3596:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/WeatherAncestor( 2688): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 18:46:8
I/ActivityManager(  932): Killing 3644:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  932): failed to open /acct/uid_10011/pid_3596/cgroup.procs: No such file or directory
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
W/libprocessgroup(  932): failed to open /acct/uid_1000/pid_3644/cgroup.procs: No such file or directory
D/Weather_cast( 2688): 2 : set auto-update time : 12/2 21:46
D/WeatherAncestor( 2688): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 18:46:8
D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: android.intent.action.BOOT_COMPLETED
W/ResourcesManager( 3857): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  932): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=3879 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  932): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 30.576ms
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 386us total 21.549ms
D/CalendarProvider2( 3857): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@d2b5dbe
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 312us total 31.429ms
D/CalendarProvider2( 3857): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 3857): Created com.android.providers.calendar.CalendarAlarmManager@1db5d3b(com.android.providers.calendar.CalendarProvider2@d2b5dbe)
I/InsertAccount( 3819): The account info in calendar DB already exists
I/Process ( 3819): Sending signal. PID: 3819 SIG: 9
I/LockScreenSettings( 3879): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
I/ActivityManager(  932): Process com.lge.defaultaccount (pid 3819) has died
I/LockScreenSettings( 3879): Received Broadcast : android.intent.action.BOOT_COMPLETED
I/ActivityManager(  932): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=3908 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  932): Waited long enough for: ServiceRecord{34e6683 u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
D/AndroidRuntime( 3877): 
D/AndroidRuntime( 3877): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3877): CheckJNI is OFF
D/BootCompleteReceiver( 3908): hasclipTray = true
W/ContextImpl( 3908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  932): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=3926 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  932): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3956 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  932): Killing 3678:com.android.managedprovisioning/u0a111 (adj 15): empty #11
W/libprocessgroup(  932): failed to open /acct/uid_10111/pid_3678/cgroup.procs: No such file or directory
V/AppCleanupService( 3926): registerAlarm
D/AndroidRuntime( 3877): Calling main entry com.android.commands.am.Am
D/AppCleanupService( 3926): noticeInterval = 2678399999
D/AppCleanupService( 3926): notiDateStr = 2015-12-20 22:35:42
D/AppCleanupService( 3926): noticeStart = 2015-12-20 22:35:42
D/AppCleanupService( 3926): noticeStart = 1450647342000
I/ActivityManager(  932): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AppUsageDbAdapter( 3926): initPreloadedAppToTheDB() : row count = 120
D/ActivityManager(  932): setTaskToReturnTo : TaskRecord{36e36bf0 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  932): setTaskToReturnTo : TaskRecord{36e36bf0 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  932): AppWindowTokenEx init.. 
D/ContextHelper(  932): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  932): Focus left window: Window{1ef5a7f3 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 3877): Shutting down VM
I/[LGHome]EVENT( 1907): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  932): check instance of lgWin Window{141a8fa u0 Starting com.example.hello}
E/UpdateRequestReceiver( 3956): ignoring update request
I/ActivityManager(  932): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3978 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1907): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
E/UpdateRequestReceiver( 3956): ignoring update request
I/HotwordDetector( 1973): Closing mic
I/MicrophoneInputStream( 1973): mic_close com.google.android.apps.gsa.speech.audio.u@12bb07ee
V/AudioRecord( 1973): stop()
D/AudioRecord( 1973): AudioRecord->stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioFlinger(  280): Record stopped OK
V/AudioPolicyManager(  280): stopInput() input 17
V/AudioPolicyService(  280): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  280): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  280): ThreadBase::setParameters() routing=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb4318000
D/audio_hw_primary(  280): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
E/UpdateRequestReceiver( 3956): ignoring update request
E/UpdateRequestReceiver( 3956): ignoring update request
E/UpdateRequestReceiver( 3956): ignoring update request
I/[LGHome]EVENT( 1907): [Launcher.java:5214:onStop()]onStop
V/audio_hw_primary(  280): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  280): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  280): disable_audio_route: exit
E/audio_hw_primary(  280): disable_snd_device: enter 144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  280): stop_input_stream: exit: status(0)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  280): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  280): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  280): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyService(  280): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  280): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  280): setParameters(): io 17, keyvalue hotword_active=0, calling pid 280
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb4318000
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioRecord( 1973): stop()
V/AudioRecord( 1973): stop()
V/AudioRecord( 1973): stop()
I/WindowStateAnimator(  932): Starting window displayed
E/UpdateRequestReceiver( 3956): ignoring update request
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioPolicyManager(  280): releaseInput() 17
V/AudioPolicyManager(  280): closeInput(17)
V/AudioFlinger(  280): closeInput() 17
V/AudioSystem(  280): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  932): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): ThreadBase::exit
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioSystem( 1781): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): RecordThread 0xb4318000 exiting
D/audio_hw_primary(  280): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  280): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): releaseInput() exit
V/AudioFlinger(  280): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  280): removeClient_l() pid 1973, calling pid 280
V/AudioSystem( 1973): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3146): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1387): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2704): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): releasing 16 from 1973 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
I/HotwordRecognitionRnr( 1973): Hotword detection finished
I/HotwordRecognitionRnr( 1973): Stopping hotword detection.
I/SystemUI[Framework](  932): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  932): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  932): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  932): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  932): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3dffcb5e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  932): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1387): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1387): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1387):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1387): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1387): draw background and invalidate : color = 14000000
,D/BarTransitions( 1387): draw background and invalidate : color = 1a191919
I/ActivityManager(  932): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4010 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  932): Killing 3701:com.lge.voicerecorder/u0a34 (adj 15): empty #11
I/ActivityManager(  932): Waited long enough for: ServiceRecord{3c98116d u0 com.lge.sizechangable.weather/.service.WeatherService}
W/libprocessgroup(  932): failed to open /acct/uid_10034/pid_3701/cgroup.procs: No such file or directory
D/ContextHelper( 3978): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/SIMObserver( 4010): action:android.intent.action.BOOT_COMPLETED
D/SIMObserver( 4010): handle ACTION_BOOT_COMPLETED
I/WebViewFactory( 3978): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  932): Killing 3725:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  932): failed to open /acct/uid_10051/pid_3725/cgroup.procs: No such file or directory
E/QcrilMsgTunnelAutoboot( 2312): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
D/PhoneInterfaceManager( 1781): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/PhoneInterfaceManager( 1781): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/LibraryLoader( 3978): Time to load native libraries: 3 ms (timestamps 3939-3942)
I/LibraryLoader( 3978): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3978): Binding Chromium to main looper Looper (main, tid 1) {1db5d3b}
I/LibraryLoader( 3978): Expected native library version number "",actual native library version number ""
I/chromium( 3978): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3978): Initializing chromium process, singleProcess=true
W/art     ( 3978): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3978): ApplicationContext is null in ApplicationStatus
W/chromium( 3978): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3978): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3978): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3978): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3978): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3978): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3978): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3978): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3978): Remote Branch: 
I/Adreno-EGL( 3978): Local Patches: 
I/Adreno-EGL( 3978): Reconstruct Branch: 
V/AudioPolicyService(  280): registerClient() client 0xb40271a0, uid 10030
D/BluetoothManagerService(  932): Message: 20
D/BluetoothManagerService(  932): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25d644aa:true
D/BluetoothAdapter( 3978): 311988759: getState() :  mService = null. Returning STATE_OFF
D/FileApkUtils( 2294): Spent 96ms computing apk sha1.
D/FileApkUtils( 2294): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 2294): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
V/AlarmManager(  932): ELAPSED_WAKEUP set : Alarm{653a250 type 2 when 54222 com.android.providers.calendar} when 54222
D/DexOptUtils( 2294): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 2294): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
W/art     ( 2294): Suspending all threads took: 7.030ms
D/GmsModuleFndr( 2294): Beginning GMS chimera module scan
D/GmsModuleFndr( 2294): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 2294): Beginning module configuration check
D/ChimeraCfgMgr( 2294): Module APKs unchanged, check complete
W/art     ( 3978): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3978): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3978): CordovaWebView is running on device made by: LGE
W/art     ( 3978): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3978): Attempt to remove local handle scope entry from IRT, ignoring
D/GCM     ( 2294): COMPAT: Multi user not supported
,D/GCM     ( 2036): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 2294): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1763): DispatchingService.onCreate()
,I/Activity( 3978): Activity.onPostResume() called 
,D/OpenGLRenderer( 3978): Render dirty regions requested: true
I/OpenGLRenderer( 3978): Initialized EGL, version 1.4
D/OpenGLRenderer( 3978): Enabling debug mode 0
,I/CheckinService( 2294): Checkin interval check for package: unspecified last checkin: 1449077374253 min interval config: 0 actual interval: 996309
D/Atlas   ( 3978): Validating map...
,D/SplitWindow(  932): check instance of lgWin Window{3ba5d3ac u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 3978): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/CheckinService( 2294): Disabling old GoogleServicesFramework version
,D/SystemUpdateService( 2294): onCreate
D/InputDispatcher(  932): Focus entered window: Window{3ba5d3ac u0 com.example.hello/com.example.hello.MainActivity}
,I/GCoreUlr( 1763): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/SystemUpdateService( 2294): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
V/AuthZen ( 2294): Handling intent: android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 2294): Handling event: android.intent.action.BOOT_COMPLETED
,V/GLSActivity( 2036): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2036): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/InputMethodManagerService(  932): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/ActivityManager(  932): Displayed com.example.hello/.MainActivity: +1s230ms
I/Timeline(  932): Timeline: Activity_windows_visible id: ActivityRecord{15584569 u0 com.example.hello/.MainActivity t220} time:54704
,I/SystemUpdateService( 2294): cancelUpdate (empty URL)
,I/SystemUpdateService( 2294): active receiver: disabled
I/Timeline( 3978): Timeline: Activity_idle id: android.os.BinderProxy@136c2f07 time:54731
D/ChimeraCfgMgr( 2294): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 1763): Explicit concurrent mark sweep GC freed 15492(993KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 11MB/18MB, paused 1.374ms total 125.374ms
,I/NotificationManager( 2294): com.google.android.gms: cancel(2130838130) by com.google.android.gms
I/NotificationManager( 2294): com.google.android.gms: cancel(2130838131) by com.google.android.gms
,I/CheckinService( 2294): Checking schedule, now: 1449078370925 next: 1449604623185
I/CheckinService( 2294): active receiver: disabled
W/BindingManager( 3978): Cannot call determinedVisibility() - never saw a connection for the pid: 3978
,D/sensors_hal_Time(  932): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  932): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  932): tsOffsetIs: Apps: 54947356807; DSPS: 1899025; Offset : -3018843969
,I/chromium( 3978): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/art     ( 2036): Explicit concurrent mark sweep GC freed 5183(311KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 11MB/18MB, paused 1.441ms total 80.945ms
W/BaseAppContext( 2294): Using Auth Proxy for data requests.
D/ChimeraCfgMgr( 2294): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 2294): onDestroy
,W/GCoreFlp( 1763): No location to return for getLastLocation()
,I/NotificationManager( 2294): com.google.android.gms: cancel(10436) by com.google.android.gms
W/FusedLocationProvider( 2294): location=null
W/GCoreFlp( 1763): No location to return for getLastLocation()
W/FusedLocationProvider( 2294): location=null
,W/Auth    ( 2036): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/GCoreUlr( 1763): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1763): Unbound from all location providers
,I/AuthZen ( 2294): Fetching signing key...
,V/GLSActivity( 2036): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AuthZen ( 2294): Signing key fetched successfully!
,V/GLSActivity( 2036): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/BaseAppContext( 2294): Using Auth Proxy for data requests.
,V/GLSActivity( 2036): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Kids    ( 2294): [AbstractKidsOperation] Invalid device state 3
I/Kids    ( 2294): [KidAccountFixer] No network connection
D/JsMessageQueue( 3978): Set native->JS mode to OnlineEventsBridgeMode
V/GmsCoreStatsServiceLauncher( 2294): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,I/GCoreUlr( 1763): DispatchingService.onDestroy()
I/GCoreUlr( 1763): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1763): Unbound from all location providers
,D/a       ( 2294): Opening database auth.proximity.permit_store...
D/PersistentNotificationBroadcastReceiver( 2036): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
D/AuthZenTransactionCache( 2294): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2294): Clearing transaction cache
,E/AndroidProtocolHandler( 3978): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/ActivityManager(  932): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4110 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 4110): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/jxcore_app_log( 3978): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1623098368
,D/JX-Cordova( 3978): jxcore cordova android initializing
V/AlarmManager(  932): ELAPSED_WAKEUP set : Alarm{177b1436 type 2 when 55725 com.google.android.gms} when 55725
,W/jxcore-log( 3978): Initializing JXcore engine
,W/jxcore-log( 3978): JXcore engine is ready
I/Babel_SMS( 4110): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4110): MmsConfig.loadMmsSettings
I/Babel_SMS( 4110): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4110): MmsConfig.loadFromDatabase
,W/jxcore-log( 3978): Starting JXcore engine
,E/Babel_SMS( 4110): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4110): MmsConfig.loadFromResources
E/Babel_SMS( 4110): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4110): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4110): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4110): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4110): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4110): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4110): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4110): found sensor: LGE Linear Acceleration Sensor, handle=30
,D/SensorManager( 4110): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4110): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4110): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4110): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4110): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4110): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4110): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4110): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4110): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4110): found sensor: Motion Accel, handle=46
,I/art     ( 4110): CheckpointMarkThreadRoots callback created = 0xaaf55430
,W/m.example.hello( 3978): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7319]" dev="sockfs" ino=7319 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3978): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3978): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5618]" dev="sockfs" ino=5618 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3978): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3978): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3978): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[20780]" dev="sockfs" ino=20780 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/Settings( 4110): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4110): startup - clean
I/art     ( 4110): CheckpointMarkThreadRoots callback created = 0xaaf55410
I/Babel   ( 4110): deleted: false for 0
,W/jxcore-log( 3978): Platform android
W/jxcore-log( 3978): 
W/jxcore-log( 3978): Process ARCH arm
W/jxcore-log( 3978): 
,W/AudioCapabilities( 4110): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 4110): Unsupported mime audio/adpcm
,W/AudioCapabilities( 4110): Unsupported mime audio/g726
W/AudioCapabilities( 4110): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4110): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4110): Unsupported mime video/mjpg
W/VideoCapabilities( 4110): Unsupported mime video/theora
,W/AudioCapabilities( 4110): Unsupported mime audio/evrc
,W/AudioCapabilities( 4110): Unsupported mime audio/qcelp
W/VideoCapabilities( 4110): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4110): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4110): Unsupported mime audio/qcelp
W/AudioCapabilities( 4110): Unsupported mime audio/evrc
W/VideoCapabilities( 4110): Unsupported mime video/mp4v-esdp
I/jxcore-log( 3978): JXcore Cordova bridge is ready!
I/jxcore-log( 3978): 
W/jxcore-log( 3978): JXcore engine is started
,I/VideoCapabilities( 4110): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4110): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4110): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4110): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4110): Unrecognized profile 2130706433 for video/avc
E/jxcore-log( 3978): >> LGE-LG-D722
E/jxcore-log( 3978): 
I/jxcore-log( 3978): Total memory 906309632
I/jxcore-log( 3978): 
,I/jxcore-log( 3978): Free memory 31076352
I/jxcore-log( 3978): 
I/jxcore-log( 3978): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3978): 
I/jxcore-log( 3978): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3978): 
I/jxcore-log( 3978): userPath [ 'www' ]
I/jxcore-log( 3978): 
I/jxcore-log( 3978): Size 720 1196
I/jxcore-log( 3978): 
,I/jxcore-log( 3978): Screen Brightness 255
I/jxcore-log( 3978): 
E/jxcore-log( 3978): Dummy Error Log.
E/jxcore-log( 3978): 
I/vclib   ( 4110): onServiceConnected
,W/Babel   ( 4110): Attempted to change video mute state without an active call.
I/NotificationManager( 4110): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  932): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4146 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 4146): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4146): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     (  932): Explicit concurrent mark sweep GC freed 23191(1146KB) AllocSpace objects, 9(333KB) LOS objects, 33% free, 22MB/34MB, paused 2.293ms total 150.638ms
,V/JNIHelp ( 4146): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 4146): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4146): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  932): Waited long enough for: ServiceRecord{3e0e341c u0 com.google.android.gms/.gcm.GcmService}
,I/jxcore-log( 3978): getBuffer is called!!!!
I/jxcore-log( 3978): 
,W/CursorWrapperInner( 3749): Cursor finalized without prior close()
,I/art     ( 4146): CheckpointMarkThreadRoots callback created = 0xb042dbf0
,W/ResourcesManager( 4146): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4146): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 4146): CheckpointMarkThreadRoots callback created = 0xb4958de0
E/YouTube MDX( 4146): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 4146): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4146): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/dex2oat ( 4178): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1490348085.jar --oat-fd=28 --oat-location=/data/data/com.google.android.youtube/cache/ads1490348085.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4146): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/art     ( 3978): Background sticky concurrent mark sweep GC freed 44387(2MB) AllocSpace objects, 17(585KB) LOS objects, 23% free, 8MB/11MB, paused 5.370ms total 44.889ms
,I/dex2oat ( 4178): dex2oat took 152.554ms (threads: 4)
,I/NotificationManager( 4146): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4146): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4146): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4146): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4146): Found 10006
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4146): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  932): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4230 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager( 4146): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/ActivityManager(  932): Killing 3749:com.lge.cloudhub/u0a49 (adj 15): empty #11
,W/libprocessgroup(  932): failed to open /acct/uid_10049/pid_3749/cgroup.procs: No such file or directory
W/ActivityManager(  932): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4230): getAccountsCursor
,V/GLSActivity( 2036): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4230): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  932): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 4230): Error finding the version of the Email provider.....
E/Gmail   ( 4230): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4230): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4230): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4230): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4230): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4230): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4230): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4230): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4230): We do not support migrating this version of the Email provider.
,I/Gmail   ( 4230): getAccountsCursor
V/GLSActivity( 2036): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  932): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  932): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 4230): Observing account changes for notifications
,I/ActivityManager(  932): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4282 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,V/GLSActivity( 2036): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  932): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  932): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4230): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@8148d82 that was originally bound here
E/ActivityThread( 4230): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@8148d82 that was originally bound here
E/ActivityThread( 4230): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4230): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4230): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4230): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4230): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4230): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4230): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4230): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4230): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4230): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4230): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4230): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4230): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4230): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4230): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4230): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  932): Unbind failed: could not find connection for android.os.BinderProxy@2b40923d
,I/Gmail   ( 4230): notifyAccountChanged
,I/Gmail   ( 4230): getAccountsCursor
V/GLSActivity( 2036): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4230): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/[BNRBootReceiver]( 4282): boot receiver action = android.intent.action.BOOT_COMPLETED
V/[BNRBootReceiver]( 4282): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4282): End of BootComplted IF
V/[BNRBootReceiver]( 4282): Boot Receiver Return
I/ActivityManager(  932): Killing 3776:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
V/[BNRBootCompletedThread]( 4282): run
W/linker  ( 4304): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,I/Gmail   ( 4230): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/bnrd    ( 4304): BNRD > wait starting [4304-3058102400] <
E/bnrd    ( 4304): /data/data/.bnr_fifo_req
I/Gmail   ( 4230): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4230): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/[BNRBootCompletedThread]( 4282): End of BNRProcess
V/[BNRBootCompletedThread]( 4282): End of BNRViaWifiProcess
V/[BNRBootCompletedThread]( 4282): End of SpriteProcess
V/[BNRBootCompletedThread]( 4282): exit
W/libprocessgroup(  932): failed to open /acct/uid_10054/pid_3776/cgroup.procs: No such file or directory
,I/ActivityManager(  932): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4310 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  932): Killing 3797:com.lge.lgfota.permission/1000 (adj 15): empty #11
W/libprocessgroup(  932): failed to open /acct/uid_1000/pid_3797/cgroup.procs: No such file or directory
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/Gmail   ( 4230): getAccountsCursor
,V/GLSActivity( 2036): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4310): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 4310): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 4310): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4310): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4310): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3172): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3172): created cursor android.database.sqlite.SQLiteCursor@98151b on behalf of 4310
D/Volley  ( 4310): [441] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4310): [448] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 4310): Skipping gmscore version check
,I/ActivityManager(  932): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4355 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  932): Killing 3837:com.lge.hiddenmenu/1000 (adj 15): empty #11
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 23.219ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.963ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.314ms
,W/libprocessgroup(  932): failed to open /acct/uid_1000/pid_3837/cgroup.procs: No such file or directory
D/Finsky  ( 4310): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4310): [1] Libraries$2.run: Finished loading 1 libraries.
W/ResourcesManager( 4355): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/Finsky  ( 4310): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 4310): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/App     ( 4355): [App][onCreate()] 4.40.21
,D/AccountManager( 4355): setSyncFrequency
,W/ContextImpl( 4355): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
,D/KeyguardUpdateMonitor( 1387): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1387): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1387): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1387): On Skip Timer : true
D/PowerService( 1834): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/WeatherAncestor( 2688): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:46:15
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherAncestor( 2688): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:46:15
,D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
W/ActivityManager(  932): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2688): 2 : buildUpdate, appWidgetId: 2
,D/WeatherTheme( 2688): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2688): 2 : Fixed theme : optimus
D/ReminderService( 4355): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
D/WeatherReflect( 2688): 2 : Map key string is -2
D/lim     ( 2688): 2 : time = 18:46
I/WeatherReflect( 2688): Model Name : LG-D722
D/LocationReminderManager( 4355): [connect] Request location client connection.
D/WeatherTheme( 2688): 2 : exactly same view!
D/WeatherTheme( 2688): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  932): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/UserPresentBroadcastReceiver( 1763): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
W/ContextImpl( 4355): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
,D/LocationReminderManager( 4355): location cilent is connected.
,D/LocationReminderManager( 4355): [removeAllReminders]
,I/ActivityManager(  932): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4397 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/GeofencerStateMachine( 1763): Ignoring removeGeofence because network location is disabled.
,I/ActivityManager(  932): Killing 3857:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/LocationReminderManager( 4355): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 4355): [removeAllReminders] Failed to remove reminder
,W/libprocessgroup(  932): failed to open /acct/uid_10014/pid_3857/cgroup.procs: No such file or directory
,I/ActivityManager(  932): Killing 3879:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  932): failed to open /acct/uid_10069/pid_3879/cgroup.procs: No such file or directory
,W/GCoreFlp( 1763): No location to return for getLastLocation()
W/GCoreFlp( 1763): No location to return for getLastLocation()
D/LGDMClient( 4397): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4397): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4397): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 4397): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4397): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
,V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4397): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  932): Killing 3908:com.lge.springcleaning/1000 (adj 15): empty #11
W/libprocessgroup(  932): failed to open /acct/uid_1000/pid_3908/cgroup.procs: No such file or directory
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
I/ActivityManager(  932): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4424 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 4424): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  932): Message: 20
D/BluetoothManagerService(  932): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35eb79b6:true
,D/BluetoothAdapter( 4424): 311988759: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4424): 311988759: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  932): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4442 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 4424): Create singleton instance
,I/AudioManager( 4424): getMode name:com.lge.qremote
,D/UEI.SmartControl( 4442): Quickset Services start...
I/UEI.SmartControl( 4442): Manufacture = LGE
,D/UEI.SmartControl( 4442): File observer start...
E/UEI.SmartControl( 4442): IR Port is disabled: false
D/UEI.SmartControl( 4442): Starting file observer...
D/UEI.SmartControl( 4442): Extracting JNI libs...
D/UEI.SmartControl( 4442): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 4442): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4442): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4442): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ActivityManager(  932): Waited long enough for: ServiceRecord{ffc6b74 u0 com.android.mms/.service.SwitchedService}
I/art     (  932): Explicit concurrent mark sweep GC freed 20853(979KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.646ms total 164.059ms
,V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
I/UEI.SmartControl( 4442): --- Selecting new region: 2
I/UEI.SmartControl( 4442): -- Running on KitKat(19) and above! JNI will be used.
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
,D/UEI.SmartControl( 4442): Platform has CIR...
D/UEI.SmartControl( 4442): NO CIR support, need to check package...
I/AudioManager( 4424): getMode name:com.lge.qremote
I/UEI.SmartControl( 4442): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4442): QS Service created
,V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
,E/UEI.SmartControl( 4442): QS start get config
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3146): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3146): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4397): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4397): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4397): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4397): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 4397): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/AudioManager( 4424): getMode name:com.lge.qremote
D/LGDMClient( 4397): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
,D/UEI.SmartControl( 4442): Loading JNI Libs...
D/UEI.SmartControl( 4442):  configuring local db...
D/WearableService( 1763): callingUid 10006, callindPid: 1763
,E/MDM     ( 1763): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/GCM     ( 2036): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2036): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 2294): Restart initialization of location
,V/GLSActivity( 2036): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 2036): com.google.android.gms: cancel(0) by com.google.android.gms
V/GmsCoreStatsServiceLauncher( 2294): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  932): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4483 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 4483): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4483): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4483): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/art     ( 2036): Explicit concurrent mark sweep GC freed 10173(624KB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 11MB/18MB, paused 1.823ms total 62.431ms
,D/UEI.SmartControl( 4442):  ---- Has DB8: true
W/GCoreFlp( 1763): No location to return for getLastLocation()
W/FusedLocationProvider( 2036): location=null
,D/UEI.SmartControl( 4442): QS start statue = true Error code = 0
D/UEI.SmartControl( 4442): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4442): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4442): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 4442): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4442): IrrcClient ++ 
D/irrcClient( 4442): getIrrcService ++ 
D/irrcClient( 4442): getIrrcService -- 
,D/irrcClient( 4442): IrrcClient -- 
W/irrc_jni( 4442): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4442): Services init done
I/UEI.SmartControl( 4442): Device manager: loading config....
D/UEI.SmartControl( 4442): QS Service init finished
,D/UEI.SmartControl( 4442): QS Service version name: 0.1.73
D/UEI.SmartControl( 4442): QS Service version code: 1073
D/UEI.SmartControl( 4442): Service requested: Control
D/UEI.SmartControl( 4442): Config is loaded...
D/UEI.SmartControl( 4442):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4442): Notify AllClients services are ready: 0
D/UEI.SmartControl( 4442): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 4442): Internal service binding...
I/LGEmail ( 4483): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/UEI.SmartControl( 4442): -----IControl: 11
D/UEI.SmartControl( 4442): Caller: com.lge.qremote
D/UEI.SmartControl( 4442): ------------ IControl registerCallback...
I/UEI.SmartControl( 4442): Registering callback...
D/UEI.SmartControl( 4442): -----IControl: 19
D/UEI.SmartControl( 4442): Caller: com.lge.qremote
I/UEI.SmartControl( 4442): Registering Services Ready callback...
I/UEI.SmartControl( 4442): Notify client services are ready...
D/UEI.SmartControl( 4442): -----IControl: 8
D/UEI.SmartControl( 4442): Caller: com.lge.qremote
,D/LGEmail ( 4483): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/ActivityManager(  932): Killing 3956:com.google.android.configupdater/u0a3 (adj 15): empty #11
W/libprocessgroup(  932): failed to open /acct/uid_10003/pid_3956/cgroup.procs: No such file or directory
,I/PackageChangeReceiver( 4483): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  932): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4509 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  932): Killing 4010:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  932): failed to open /acct/uid_1000/pid_4010/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  932): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  932): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  932): Message: 2
D/WifiServiceImplEx(  932): setWifiEnabled: false pid=3978, uid=10030, package= com.example.hello, App Lable : HelloWorld
,D/WifiService(  932): setWifiEnabled: false pid=3978, uid=10030
I/jxcore-log( 3978): ****TEST TOOK:  5110  ms ****
I/jxcore-log( 3978): 
I/jxcore-log( 3978): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3978): 
I/ActivityManager(  932): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4536 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  932): Killing 4110:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  932): failed to open /acct/uid_10061/pid_4110/cgroup.procs: No such file or directory
,V/AlarmManager(  932): ELAPSED_WAKEUP set : Alarm{100f66ee type 2 when 56082 com.google.android.talk} when 56082
V/AlarmManager(  932): RTC_WAKEUP set : Alarm{2cb47a1c type 0 when 1449078377485 com.google.android.gms} when 1449078377485
,I/AppUp4:AppBoxCP( 4536): onCreate
W/AppUp4:DB( 4536):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 4536):  setFingerPrint start
I/AppUp4:DB( 4536):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 4536):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4536):  SDK version = 0
I/AppUp4:DB( 4536):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 4536): AppBoxApplication onCreate()
,I/art     ( 2294): Explicit concurrent mark sweep GC freed 18290(1533KB) AllocSpace objects, 21(336KB) LOS objects, 39% free, 11MB/19MB, paused 1.413ms total 101.960ms
,D/AppUp4:PreloadHelper( 4536): removed from Exclude : com.example.hello : 1
I/ActivityManager(  932): Killing 4146:com.google.android.youtube/u0a100 (adj 15): empty #11
D/AndroidRuntime( 4553): 
D/AndroidRuntime( 4553): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4553): CheckJNI is OFF
W/libprocessgroup(  932): failed to open /acct/uid_10100/pid_4146/cgroup.procs: No such file or directory
,I/ActivityManager(  932): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4568 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/iu.UploadsManager( 2294): End new media; added: 0, uploading: 0, time: 306 ms
,W/ResourcesManager( 4568): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4568): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 4568): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 4568): Total System Memory = 906309632
,I/GalleryUtils( 4568): Application Heap = 96 MB
I/AppConfig( 4568): App Tier : NOT_DEF
D/AndroidRuntime( 4553): Calling main entry com.android.commands.pm.Pm
,D/SystemHelper( 4568): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  932): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4599 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  932): Killing 4230:com.google.android.gm/u0a53 (adj 15): empty #11
W/PackageSettings(  932): Skipping PackageSetting{c92fdd9 com.test.thalitest/10316} due to missing metadata
,I/ActivityManager(  932): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  932): Killing 3978:com.example.hello/u0a30 (adj 0): stop com.example.hello
,I/WindowState(  932): WIN DEATH: Window{3ba5d3ac u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  932): Focus left window: Window{3ba5d3ac u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  932): Window went away: Window{3ba5d3ac u0 com.example.hello/com.example.hello.MainActivity}
,W/ActivityManager(  932): Force removing ActivityRecord{15584569 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/libprocessgroup(  932): failed to open /acct/uid_10053/pid_4230/cgroup.procs: No such file or directory
I/ActivityManager(  932): Force stopping com.example.hello appid=10030 user=0: pkg removed
,W/ActivityManager(  932): Spurious death for ProcessRecord{13b4b625 3978:com.example.hello/u0a30}, curProc for 3978: null
,D/KeyguardModel( 1387): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/GeofencerStateMachine( 1763): Ignoring removeGeofence because network location is disabled.
,I/QCNEJ   ( 1871): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3450): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
I/[LGHome]EVENT( 1907): [Launcher.java:5203:onStart()]onStart
W/System.err( 3450): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3450): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3450): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3450): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3450): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3450): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3450): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3450): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3450): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3450): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3450): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  932): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1907): [Launcher.java:776:onResume()]onResume
D/administrator(  932): Handling package changes for user 0
,I/ActivityManager(  932): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4620 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 4599): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4599): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4599): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 4599): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4599): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]QSlideListController( 1387): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]LGActivityUtil( 1907): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1907): [Launcher.java:929:onResume()]onResume end
I/Activity( 1907): Activity.onPostResume() called 
I/SystemUI[Framework](  932): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  932): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  932): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  932): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  932): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3dffcb5e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  932): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  932): Focus entered window: Window{1ef5a7f3 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/[LGHome]LGWallpaperInfo( 1907): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1907): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1387): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1387): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1907): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1907): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1907): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/art     ( 1817): CheckpointMarkThreadRoots callback created = 0xaaf1eb50
,I/[LGHome]EVENT( 1907): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1907): [setNavigationBarColor] color=0x 0
I/LockScreenSettings( 4620): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/art     ( 1817): CheckpointMarkThreadRoots callback created = 0xaaf544f0
,D/KeyguardModel( 1387): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1387): createShortcutInfo...
D/KeyguardModel( 1387): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1387): createShortcutInfo...
I/art     ( 1817): Background partial concurrent mark sweep GC freed 47980(2MB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/14MB, paused 6.624ms total 72.643ms
,W/ResourceType( 1387): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1387): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1387): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1387): createShortcutInfo...
W/ResourceType( 1387): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1387): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1387): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1387): createShortcutInfo...
W/ResourceType( 1387): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1387): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1387): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1387): createShortcutInfo...
,D/KeyguardModel( 1387): handleShortcutListChanged...
D/KeyguardModel( 1387): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1387): createShortcutInfo...
D/KeyguardModel( 1387): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1387): createShortcutInfo...
,W/ResourceType( 1387): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1387): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1387): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1387): createShortcutInfo...
W/ResourceType( 1387): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1387): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1387): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1387): createShortcutInfo...
W/ResourceType( 1387): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1387): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1387): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1387): createShortcutInfo...
I/ActivityManager(  932): Killing 4282:com.lge.bnr/1000 (adj 15): empty #11
,D/KeyguardModel( 1387): handleShortcutListChanged...
,W/libprocessgroup(  932): failed to open /acct/uid_1000/pid_4282/cgroup.procs: No such file or directory
I/art     (  932): Explicit concurrent mark sweep GC freed 17213(1104KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.292ms total 357.213ms
,I/SystemConfig( 4599): BUILD Country: EU
,I/SystemConfig( 4599): BUILD Operator: OPEN
D/AndroidRuntime( 4553): Shutting down VM
,W/InputMethodManagerService(  932): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  932): Got RemoteException sending setActive(false) notification to pid 3978 uid 10030
I/HotwordRecognitionRnr( 1973): Starting hotword detection.
,I/MicrophoneInputStream( 1973): mic_starting com.google.android.apps.gsa.speech.audio.u@1bd27038
V/AudioRecord( 1973): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1973): set(): mSessionId 22
V/AudioPolicyManager(  280): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  280): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  280): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  280): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e420)
V/audio_hw_primary(  280): adev_open_input_stream: exit
V/AudioFlinger(  280): openInput_l() openInputStream returned input 0xb546e420, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  280): openInput_l() created record thread: ID 23 thread 0xb3c79000
V/AudioSystem(  280): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1387): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
I/AudioFlinger(  280): AudioFlinger's thread 0xb3c79000 ready to run
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioSystem( 1781): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem(  932): ioConfigChanged() event 3, ioHandle 23
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioSystem( 1973): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 2704): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3146): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioFlinger(  280): openRecord() lSessionId: 22 input 23
,V/AudioFlinger(  280): getOrphanEffectChain_l session 22 index -2
V/AudioFlinger(  280): acquiring 22 from 1973, for -1
V/AudioFlinger(  280):  added new entry for 22
V/AudioRecord( 1973): start, sync event 0 trigger session 0
V/AudioRecord( 1973): mAudioRecord->start()
V/AudioFlinger(  280): RecordHandle::start()
V/AudioFlinger(  280): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  280): startInput() module primary->input primary(23)
V/AudioPolicyManager(  280): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  280): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  280): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  280): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  280): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  280): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  280): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  280): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  280): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3c79000
V/AudioFlinger::PatchPanel(  280): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  280): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  280): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  280): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  280): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyService(  280): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  280): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  280): setParameters(): io 23, keyvalue hotword_active=1, calling pid 280
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3c79000
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): AudioPolicyManager::startInput() input source = 1999
I/Timeline( 1907): Timeline: Activity_idle id: android.os.BinderProxy@14acbee1 time:62866
I/NotificationService(  932): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  932): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/MicrophoneInputStream( 1973): mic_started com.google.android.apps.gsa.speech.audio.u@1bd27038
V/msm8974_platform(  280): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  280): start_input_stream: enter: stream(0xb546e420)usecase(7: audio-record)
V/voice   (  280): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  280): start_input_stream: usecase(7)
E/audio_hw_primary(  280): select_devices: enter and usecase(7)
,V/msm8974_platform(  280): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  280): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  280): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  280): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  280): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  280): enable_snd_device: enter  144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  280): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/JobSchedulerService(  932): Receieved: android.intent.action.PACKAGE_REMOVED
D/ACDB-LOADER(  280): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  280): ACDB -> send_adm_topology
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  280): ACDB -> send_asm_topology
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  280): ACDB -> send_audtable
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  280): ACDB -> send_audvoltable
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  280): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  280): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AFE_CAL
I/SystemUI[Framework](  932): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  932): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  932): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  932): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  932): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3dffcb5e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  932): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/LockScreenSettings( 4620): New app installed broadcast received ..
V/audio_hw_primary(  280): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  280): enable_audio_route: exit
D/audio_hw_primary(  280): select_devices: done
V/audio_hw_primary(  280): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
D/TaskPersister(  932): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1387): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1387): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
V/audio_hw_primary(  280): start_input_stream: exit
I/[SystemUI]NavigationThemeResource( 1387): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1387):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1387): , Keyguard show=false, IME shown=false, Panel expanded=false
I/SystemConfig( 4599): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 4599): existFile = false
I/SystemConfig( 4599): canReadFile = false
I/SystemConfig( 4599): systemFeature RCS result false
D/SystemConfig( 4599): refreshRcsSupport() :false
I/LockScreenSettings( 4620): Number of installed packages  1
,D/BarTransitions( 1387): draw background and invalidate : color = e8000000
D/BarTransitions( 1387): draw background and invalidate : color = e8dedede
,I/ActivityManager(  932): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4652 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  932): Killing 4310:com.android.vending/u0a36 (adj 15): empty #11
I/HotwordWorker( 1973): onReady
,W/libprocessgroup(  932): failed to open /acct/uid_10036/pid_4310/cgroup.procs: No such file or directory
D/LCardEmulationManager( 1817): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1817): getDefaultRoute
D/EulaProviderUpdateObserver( 4652): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 4652): uri : package:com.example.hello
,I/ActivityManager(  932): Killing 4355:com.lge.qmemoplus/1000 (adj 15): empty #11
W/libprocessgroup(  932): failed to open /acct/uid_1000/pid_4355/cgroup.procs: No such file or directory
,I/Timeline(  932): Timeline: Activity_windows_visible id: ActivityRecord{1df832a7 u0 com.lge.launcher2/.Launcher t219} time:63134
,D/PackageBroadcastService( 2294): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 2294): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2294): Module APK com.google.android.play.games already loaded
W/ResourcesManager(  932): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  932): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1907): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/ChimeraCfgMgr( 2294): Loading module com.google.android.gms.games from APK com.google.android.play.games

```
