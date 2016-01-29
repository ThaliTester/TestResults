#### Test 57659382b63fd0b_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
W/ActivityManager(  847): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  847): RTC_WAKEUP set : Alarm{3abd2aeb type 0 when 1453736942356 com.android.providers.contacts} when 1453736942356
V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{2611048 type 2 when 59550 com.google.android.talk} when 59550
V/AlarmManager(  847): RTC_WAKEUP set : Alarm{f071406 type 0 when 1454082593235 com.android.vending} when 1454082593235
W/ResourcesManager( 5126): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5126): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
D/Finsky  ( 4907): [580] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4907): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 5511): 
D/AndroidRuntime( 5511): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5511): CheckJNI is OFF
I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
D/AndroidRuntime( 5511): Calling main entry com.android.commands.am.Am
I/ActivityManager(  847): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  847): setTaskToReturnTo : TaskRecord{aa69dde #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  847): setTaskToReturnTo : TaskRecord{aa69dde #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  847): AppWindowTokenEx init.. 
D/ContextHelper(  847): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  847): Focus left window: Window{245f3c5d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5511): Shutting down VM
D/SplitWindow(  847): check instance of lgWin Window{229d1b78 u0 Starting com.test.thalitest}
I/ActivityManager(  847): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5526 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{12137251 type 2 when 88864 com.android.providers.calendar} when 88864
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/CalendarProviderBroadcastReceiver( 5402): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5402): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5402): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 5402): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5402): [getOrCreateCalendarAlarmManager]
I/WindowStateAnimator(  847): Starting window displayed
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3455683,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1369): draw background and invalidate : color = 1f000000
D/BarTransitions( 1369): draw background and invalidate : color = 11111111
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1933): Closing mic
I/MicrophoneInputStream( 1933): mic_close com.google.android.apps.gsa.speech.audio.u@ca6fedc
V/AudioRecord( 1933): stop()
D/AudioRecord( 1933): AudioRecord->stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
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
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3833000
,D/audio_hw_primary(  278): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  278): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  278): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  278): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  278): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  278): disable_audio_route: exit
E/audio_hw_primary(  278): disable_snd_device: enter 144
D/hardware_info(  278): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  278): disable_snd_device: snd_device(144: lg-vr-handset-mic)
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
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3833000
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioRecord( 1933): stop()
,D/CalendarProvider2( 5402): [IntentService] Release Lock
V/AudioRecord( 1933): stop()
V/AudioRecord( 1933): stop()
D/CalendarProvider2( 5402): CalendarProviderIntentService.onDestroy()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
V/AudioPolicyManager(  278): releaseInput() 17
V/AudioPolicyManager(  278): closeInput(17)
V/AudioFlinger(  278): releasing 16 from 1933 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/AudioFlinger(  278): closeInput() 17
V/AudioSystem(  278): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1369): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1933): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): ThreadBase::exit
V/AudioSystem( 3118): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioSystem( 2666): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  847): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1746): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): RecordThread 0xb3833000 exiting
D/audio_hw_primary(  278): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioPolicyService(  278): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  278): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  278): releaseInput() exit
V/AudioFlinger(  278): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  278): removeClient_l() pid 1933, calling pid 278
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1933): Stopping hotword detection.
,I/HotwordRecognitionRnr( 1933): Hotword detection finished
D/ContextHelper( 5526): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 5526): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5526): Time to load native libraries: 2 ms (timestamps 9326-9328)
I/LibraryLoader( 5526): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5526): Binding Chromium to main looper Looper (main, tid 1) {1186a9c4}
,I/LibraryLoader( 5526): Expected native library version number "",actual native library version number ""
I/chromium( 5526): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5526): Initializing chromium process, singleProcess=true
W/art     ( 5526): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5526): ApplicationContext is null in ApplicationStatus
W/chromium( 5526): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5526): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5526): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5526): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5526): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5526): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5526): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5526): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5526): Remote Branch: 
I/Adreno-EGL( 5526): Local Patches: 
I/Adreno-EGL( 5526): Reconstruct Branch: 
,V/AudioPolicyService(  278): registerClient() client 0xb3826aa0, uid 10316
,D/BluetoothManagerService(  847): Message: 20
D/BluetoothManagerService(  847): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@314a52a8:true
D/BluetoothAdapter( 5526): 19308080: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5526): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5526): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5526): CordovaWebView is running on device made by: LGE
,W/art     ( 5526): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5526): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5526): Activity.onPostResume() called 
,D/OpenGLRenderer( 5526): Render dirty regions requested: true
,I/OpenGLRenderer( 5526): Initialized EGL, version 1.4
D/OpenGLRenderer( 5526): Enabling debug mode 0
D/Atlas   ( 5526): Validating map...
,D/SplitWindow(  847): check instance of lgWin Window{330bb5d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5526): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  847): Focus entered window: Window{330bb5d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  847): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  847): Displayed com.test.thalitest/.MainActivity: +1s177ms
I/Timeline(  847): Timeline: Activity_windows_visible id: ActivityRecord{4bf0bbf u0 com.test.thalitest/.MainActivity t222} time:90043
I/Timeline( 5526): Timeline: Activity_idle id: android.os.BinderProxy@9f5f360 time:90074
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  847): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/BindingManager( 5526): Cannot call determinedVisibility() - never saw a connection for the pid: 5526
,D/JsMessageQueue( 5526): Set native->JS mode to OnlineEventsBridgeMode
,D/AlertService( 5452): Beginning updateAlertNotification
,D/AlertService( 5452): No fired or scheduled alerts
I/NotificationManager( 5452): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(1) by com.android.calendar
,I/NotificationManager( 5452): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5452): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5452): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 5452): No events found starting within 1 week.
,D/jxcore_app_log( 5526): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426131456
,I/chromium( 5526): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 5526): CheckpointMarkThreadRoots callback created = 0x9f67e500
,I/art     ( 5526): CheckpointMarkThreadRoots callback created = 0x9f67e4d0
,W/jxcore-log( 5526): Initializing JXcore engine
,W/jxcore-log( 5526): JXcore engine is ready
W/Thread-656( 5605): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8297]" dev="sockfs" ino=8297 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-656( 5605): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-656( 5605): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7540]" dev="sockfs" ino=7540 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-656( 5605): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-656( 5605): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-656( 5605): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26313]" dev="sockfs" ino=26313 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5526): Starting JXcore engine
,W/jxcore-log( 5526): Platform android
W/jxcore-log( 5526): 
,W/jxcore-log( 5526): Process ARCH arm
W/jxcore-log( 5526): 
I/ActivityManager(  847): Killing 5288:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10069/pid_5288/cgroup.procs: No such file or directory
,V/AlarmManager(  847): RTC_WAKEUP set : Alarm{338a9169 type 0 when 1454082598397 com.android.vending} when 1454082598397
D/Finsky  ( 4907): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  847): android: cancelAsUser(2) by android
,I/jxcore-log( 5526): JXcore Cordova bridge is ready!
I/jxcore-log( 5526): 
,W/jxcore-log( 5526): JXcore engine is started
D/libc-netbsd( 4907): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4907): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4907): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4907): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  847): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,W/Finsky  ( 4907): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  847): android: cancelAsUser(2) by android
D/libc-netbsd( 4907): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4907): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  847): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5616 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  847): android: cancelAsUser(2) by android
,I/jxcore-log( 5526): Toggling radios to true
I/jxcore-log( 5526): 
,D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  847): Message: 1
,D/BluetoothManagerService(  847): MESSAGE_ENABLE: mBluetooth = null
I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/LocationManagerService(  847): getAllProviders()=[passive, gps, network]
,D/Ulp_jni (  847): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/BluetoothAdapterService(19308080)( 1983): onBind()
D/Ulp_jni (  847): JNI:system_update. Event-4
D/WifiServiceImplEx(  847): setWifiEnabled: true pid=5526, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  847): setWifiEnabled: true pid=5526, uid=10316
D/LocationManagerService(  847): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  847): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  847): JNI:system_update. Event-4
,D/WifiServiceImplEx(  847): disconnect pid=5526, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  847): reconnect pid=5526, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5526): Radios toggled
I/jxcore-log( 5526): 
I/jxcore-log( 5526): My device name is: LGE-LG-D722
I/jxcore-log( 5526): 
I/LGFTMITEM(  847): [GET_FTM][id=6], offset=12288
E/WifiHW  (  847): Wifi MAC Address = a0:39:f7:70:12:80
E/WifiHW  (  847): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  847): band=b
E/WifiHW  (  847): ": cur_etheraddr=a0:39:f7:70:12:80
,D/SoftapController(  274): Softap fwReload - Ok
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/CommandListener(  274): Setting iface cfg
D/CommandListener(  274): Trying to bring down wlan0
D/CommandListener(  274): Clearing all IP addresses on wlan0
E/WifiHW  (  847): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,I/art     (  847): Explicit concurrent mark sweep GC freed 15421(812KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 7.727ms total 177.904ms
,D/BluetoothManagerService(  847): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  847): Message: 40
D/BluetoothManagerService(  847): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/libc-netbsd( 4907): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4907): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4907): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ResourcesManager( 5616): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5616): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/bluedroid( 1983): config_hci_snoop_log
I/wpa_supplicant( 5646): Successfully initialized wpa_supplicant
,D/BluetoothManagerService(  847): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  847): Broadcasting onBluetoothServiceUp() to 9 receivers.
V/LGMDMManagerInternal( 1983): Create singleton instance
,I/wpa_supplicant( 5646): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 5646): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,I/MultiDex( 5616): VM with version 2.1.0 has multidex support
I/MultiDex( 5616): install
I/MultiDex( 5616): VM has multidex support, MultiDex support library is disabled.
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
D/BluetoothAdapterService(19308080)( 1983): enable() - Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1983): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 1983): Setting state to 11
I/BluetoothAdapterState( 1983): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(19308080)( 1983): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  847): Message: 60
D/BluetoothAdapterService(19308080)( 1983): processStart()
D/BluetoothManagerService(  847): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  847): Bluetooth State Change Intent: 10 -> 11
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1983): Unable to read settings
D/BtSettings.ProfileConfig( 1983): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1983): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1983): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1983): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1983): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 1983): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1983): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1983): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1983): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1983): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1983): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/BluetoothAdapterService( 1983): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1983): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1983): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1983): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1983): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1983): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1983): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1983): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1983): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1983): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(19308080)( 1983): processStart() - Make Bond State Machine
D/BluetoothBondStateMachine( 1983): make
,D/BluetoothAdapterService( 1983): setAdapterService() - set to: null
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
D/LGBluetoothServiceAdapter( 1983): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 1983): StableState(): Entering Off State
D/BluetoothAdapterService( 1983): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1983): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1983): Unable to read settings
D/BtSettings.ProfileConfig( 1983): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1983): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1983): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1983): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1983): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1983): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 1983): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1983): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1983): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1983): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1983): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1983): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1983): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(19308080)( 1983): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
I/ActivityManager(  847): Process com.google.android.gm (pid 5331) has died
,D/WifiMonitor(  847): startMonitoring(wlan0) with mConnected = false
D/BluetoothAdapterService( 1983): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1983): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1983): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(19308080)( 1983): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
,I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.WIFI_STATE_CHANGED at null
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:49:59.544 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
I/ActivityManager(  847): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5650 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/WifiServerServiceExt(  847): WIFI_STATE_CHANGED_ACTION [2]
D/BluetoothHeadset(  847): Proxy object connected
,D/LGBluetoothAPIService( 1800): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
D/HeadsetService( 1983): Received start request. Starting profile...
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/BluetoothHeadset( 1746): Proxy object connected
D/BluetoothAdapterService( 1983): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1983): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1983): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(19308080)( 1983): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
I/LGBluetoothHeadsetServiceJni( 1983): classInitNative: succeeds
,D/BluetoothAdapterService( 1983): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1983): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1983): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(19308080)( 1983): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1983): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1983): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1983): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(19308080)( 1983): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/LGBluetoothFeatureConfig( 1983): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 1983): classInitNative: succeeds
,D/HeadsetStateMachine( 1983): make
I/[SystemUI]BluetoothHandler( 1369): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
D/BluetoothHeadset( 1746): Proxy object connected
D/BluetoothAdapterService( 1983): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1983): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1983): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(19308080)( 1983): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
D/BluetoothHeadset( 1746): Proxy object connected
D/BluetoothAdapterService( 1983): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1983): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1983): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(19308080)( 1983): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1983): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1983): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1983): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(19308080)( 1983): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 1983): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1983): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1983): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(19308080)( 1983): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1983): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1983): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 1983): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1983): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(19308080)( 1983): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
V/LGMDMManager( 1983): Create singleton instance
,I/BluetoothAdapterState( 1983): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 1983): max_hf_connections = 1
I/bluedroid( 1983): get_profile_interface handsfree
,I/bt-btif ( 1983): btif_hf_get_interface
I/bt-btif ( 1983): init
D/bt-btif ( 1983): max_hf_clients = 1
D/bt-btif ( 1983): btif_max_hf_clients = 1
D/bt-btif ( 1983): btif_enable_service: current services:0xa0676330
V/ToneGenerator( 1983): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  278): registerClient() client 0xb4027260, uid 1002
V/AudioPolicyManager(  278): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  278): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  278): getOutput() returns output 2
V/AudioFlinger(  278): registerClient() client 0xb57ea100, pid 1983
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  278): thread 0xb5651000 type 0 TID 1288 waking up
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  278): thread 0xb56eb000 type 0 TID 1289 waking up
V/AudioFlinger(  278): thread 0xb5735000 type 0 TID 1291 waking up
V/AudioSystem( 1983): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioSystem(  278): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  278): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1369): ioConfigChanged() event 0, ioHandle 4
V/ToneGenerator( 1983): Create Track: 0xb4908a80
V/AudioSystem( 1369): ioConfigChanged() opening already existing output! 4
V/AudioTrack( 1983): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 1983): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
V/AudioSystem( 1746): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1746): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1933): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1933): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1983): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1983): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioSystem(  847): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  847): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
I/AudioFlinger(  278): isAudioPlaybackHookOn() false
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb56eb000
D/AudioTrack( 1983): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioSystem( 2666): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2666): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3118): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3118): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  278): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  278): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1369): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1369): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem(  847): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  847): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1746): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1746): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1933): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1933): ioConfigChanged() opening already existing output!, 2
V/AudioSystem( 1983): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2666): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2666): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3118): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3118): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  278): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  278): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1933): ioConfigChanged() event 0, ioHandle 6
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem( 1933): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  847): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  847): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1369): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1369): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1746): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1746): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2666): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2666): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 3118): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3118): ioConfigChanged() opening already existing output! 6
V/AudioPolicyManager(  278): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  278): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  278): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  278): getOutput() returns output 2
V/AudioSystem( 1983): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1983): getLatency() output 2, latency 50
V/AudioSystem( 1983): getFrameCount() output 2, frameCount 960
V/AudioTrack( 1983): createTrack_l() output 2 afLatency 50
V/AudioTrack( 1983): Create normal PCM 0x1 Track
V/AudioFlinger(  278): createTrack() lSessionId: 22
V/AudioFlinger(  278): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 1
V/AudioSystem( 1983): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1983): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioTrack( 1983): Flags here  0x4 
V/AudioTrack( 1983): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  278): acquiring 22 from 1983, for 1983
V/AudioFlinger(  278):  added new entry for 22
V/ToneGenerator( 1983): ToneGenerator INIT OK, time: 94246
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb5651000
D/HeadsetStateMachine( 1983): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 1983): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1983): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1983): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  278): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1983
D/A2dpService( 1983): Received start request. Starting profile...
D/BluetoothA2dp(  847): Proxy object connected
D/audio_hw_primary(  278): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  278): voice_set_parameters: enter: bt_samplerate=8000
I/BluetoothAvrcpServiceJni( 1983): classInitNative: succeeds
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  278): platform_set_parameters: enter: bt_samplerate=8000
V/JNIHelp ( 5616): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
V/Avrcp   ( 1983): make
,D/Avrcp   ( 1983): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 1983): get_profile_interface avrcp
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
I/bt-btif ( 1983): btif_rc_get_interface
I/bt-btif ( 1983): ## init ##
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
V/ToneGenerator( 1983): ToneGenerator destructor
V/ToneGenerator( 1983): stopTone
V/ToneGenerator( 1983): Delete Track: 0xb4908a80
I/LGBluetoothAvrcpServiceJni( 1983): classInitNative: succeeds
V/AudioTrack( 1983): ~AudioTrack, releasing session id from 1983 on behalf of 1983
V/AudioFlinger(  278): releasing 22 from 1983 for 1983
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/AudioFlinger(  278): remove track (4099) and delete from mixer
V/AudioPolicyService(  278): AudioCommandThread() adding release output 2
V/AudioPolicyService(  278): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  278): PlaybackThread::Track destructor
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioFlinger(  278): removeClient_l() pid 1983, calling pid 278
V/AudioPolicyService(  278): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  278): releaseOutput() 2
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
I/LGBluetoothAvrcpAdapter( 1983): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 1983): initNative: succeeds
I/BluetoothAvrcpBrcmAdapterJni( 1983): classInitBrcmNative
I/BluetoothAvrcpBrcmAdapterJni( 1983): initBrcmNative
W/ActivityThread( 5616): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5616): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7663866: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5616): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5616): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5616): com.google.android.gms: cancel(39789) by com.google.android.gms
V/AudioService(  847): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
E/AudioService(  847): No RCC entry present to update
,E/RemoteController( 1983): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 1983): classInitNative
I/BluetoothA2dpServiceJni( 1983): classInitNative: succeeds
D/A2dpStateMachine( 1983): make
I/bluedroid( 1983): get_profile_interface a2dp
I/bt-btif ( 1983): btif_av_get_src_interface
I/bt-btif ( 1983): init
D/bt-btif ( 1983): btif_enable_service: current services:0xa0676330
I/LGBluetoothA2dpServiceJni( 1983): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1983): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 1983): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 1983): [BTUI] init
D/LGBluetoothPowerControlManager( 1983): [BTUI] init : getProfileProxy
,D/BluetoothManagerService(  847): Message: 30
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
D/A2dpStateMachine( 1983): Enter Disconnected: -2
I/BluetoothHidServiceJni( 1983): classInitNative: succeeds
D/HidService( 1983): Received start request. Starting profile...
I/bluedroid( 1983): get_profile_interface hidhost
I/bt-btif ( 1983): btif_hh_get_interface
I/bt-btif ( 1983): init
D/bt-btif ( 1983): btif_enable_service: current services:0xa0676330
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
I/BluetoothHealthServiceJni( 1983): classInitNative: succeeds
D/ChimeraCfgMgr( 5616): Reading stored module config
D/HealthService( 1983): Received start request. Starting profile...
I/bluedroid( 1983): get_profile_interface health
I/bt-btif ( 1983): btif_hl_get_interface
I/bt-btif ( 1983): init
D/bt-btif ( 1983): Process name (droid.bluetooth)
D/bt-btif ( 1983): btif_hl_soc_thread_init
D/bt-btif ( 1983): create_thread: entered
D/bt-btif ( 1983): create_thread: thread created successfully
D/bt-btif ( 1983): entered btif_hl_select_thread
D/bt-btif ( 1983): btif_hl_select_wakeup_init
D/bt-btif ( 1983): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 1983): max_s=55 
D/bt-btif ( 1983): set curr_set = org_set 
I/LGBluetoothHealthServiceJni( 1983): classInitNative: succeeds
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
,I/BluetoothPanServiceJni( 1983): classInitNative(L105): succeeds
D/PanService( 1983): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1983): initializeNative(L110): pan
,I/bluedroid( 1983): get_profile_interface pan
D/bt-btif ( 1983): stack_initialized = 0, btpan_cb.enabled:0
I/LGBluetoothPanAdapter( 1983): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
,I/BtGatt.JNI( 1983): classInitNative(L901): classInitNative: Success!
D/PowerManagerServiceEx(  847): acquireWakeLockInternal: lock=559442643, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=847
D/BtGatt.DebugUtils( 1983): handleDebugAction() action=null
D/BtGatt.GattService( 1983): Received start request. Starting profile...
D/BtGatt.GattService( 1983): start()
I/bluedroid( 1983): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 1983): advertise manager created
D/ChimeraCfgMgr( 5616): Loading module com.google.android.gms.car from APK com.google.android.gms
I/LGBluetoothGattAdapter( 1983): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 1983): setGattService:  set to: null
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
I/LGBluetoothMapAdapter( 1983): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1983): BluetoothMapBinder()
,D/BluetoothMapService( 1983): Received start request. Starting profile...
D/BluetoothMapService( 1983): start()
D/BluetoothMapEmailSettingsLoader( 1983): Found 0 applications
D/BluetoothMapEmailAppObserver( 1983): createReceiver()
D/BluetoothMapEmailAppObserver( 1983): initObservers()
,D/BluetoothMapEmailAppObserver( 1983): getEnabledAccountItems()
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
I/BluetoothSAPServiceJni( 1983): classInitNative(L170): succeeds
,D/SapService( 1983): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1983): initializeNative(L175): sap
I/bluedroid( 1983): get_profile_interface sap
I/bt-btif ( 1983): btif_sc_get_interface
I/bt-btif ( 1983): init
D/bt-btif ( 1983): btif_enable_service: current services:0xa0676330
I/LGBluetoothSapAdapter( 1983): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1983): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1983): [BTUI] initSapManager
I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/LgeBluetoothSimManager( 1746): [BTUI] SAP_ENABLE_EVT
V/BluetoothFTPServiceJni( 1983): classInitNative
I/BluetoothFTPServiceJni( 1983): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
,D/BluetoothFTPService( 1983): BluetoothFtpBinder()
D/**BluetoothFTPService( 1983): Received start request. Starting profile...
V/BluetoothFTPService( 1983): FTP-Server Service start
D/BluetoothFTPServiceJni( 1983): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1983): get_profile_interface ftp
I/bt-btif ( 1983): btif_fts_get_interface
I/bt-btif ( 1983): init
D/bt-btif ( 1983): btif_enable_service: current services:0xa0676330
D/BluetoothFTPServiceJni( 1983): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
D/LGBluetoothFeatureConfig( 1983): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 1983): classInitNative
I/BluetoothOPPServiceJni( 1983): classInitNative(L373): succeeds
V/OppService( 1983): Opp initBinder
D/**OppService( 1983): Received start request. Starting profile...
D/OppService( 1983): Starting OppService 
D/LGBluetoothOppAdapter( 1983): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/NotificationManager( 1983): com.android.bluetooth: cancelAll by com.android.bluetooth
V/BluetoothOppNotification( 1983): send message
D/BluetoothOppPreference( 1983): Dumping Names:  
D/BluetoothOppPreference( 1983): {}
D/BluetoothOppPreference( 1983): Dumping Channels:  
,D/BluetoothOppPreference( 1983): {}
D/OppService( 1983): Start()
W/BluetoothOPPServiceJni( 1983): initOppNative
D/BluetoothOPPServiceJni( 1983): initOppNative(L383): OPP
I/bluedroid( 1983): get_profile_interface opp
I/bt-btif ( 1983): btif_op_get_interface
D/BluetoothOPPServiceJni( 1983): initOppNative(L411): mOppCallbacksObj 1049850
D/BluetoothOPPServiceJni( 1983): initOppNative(L413): calling OPP init
I/bt-btif ( 1983): btif_opp_init
D/bt-btif ( 1983): btif_enable_service: current services:0xa0676330
D/BluetoothOPPServiceJni( 1983): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 1983): initOppNative(L430): mOppCallbacksObj 1049850
V/OppService( 1983): setOppService(): set to: com.broadcom.bt.service.opp.OppService@16e38716
D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
V/OppService( 1983): pendingUpdate is :  true
D/HeadsetStateMachine( 1983): Proxy object connected
D/LGBluetoothHfpAdapter( 1983): [BTUI] queryPhoneState
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - Message: 1
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(19308080)( 1983): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 1983): isTurningOnRadio()=false
D/BluetoothAdapterState( 1983): isTurningOffRadio()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1983): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1983): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothA2dp( 1983): Proxy object connected
D/LGBluetoothPowerControlManager( 1983): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@230d6897
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - Message: 1
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(19308080)( 1983): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 1983): isTurningOnRadio()=false
D/BluetoothAdapterState( 1983): isTurningOffRadio()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1983): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 1983): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1983): Disconnected process message: 11, size: 0
V/BluetoothOppProvider( 1983): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1983): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - Message: 1
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(19308080)( 1983): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 1983): isTurningOnRadio()=false
D/BluetoothAdapterState( 1983): isTurningOffRadio()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1983): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTur,ningOff=false,Bluetooth isTurningOn=true
,D/BluetoothAdapterService( 1983): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - Message: 1
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(19308080)( 1983): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 1983): isTurningOnRadio()=false
D/BluetoothAdapterState( 1983): isTurningOffRadio()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1983): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1983): Deleted complete outbound shares, number =  0
D/BluetoothAdapterService( 1983): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - Message: 1
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(19308080)( 1983): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 1983): isTurningOnRadio()=false
D/BluetoothAdapterState( 1983): isTurningOffRadio()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1983): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1983): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 1983): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - Message: 1
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(19308080)( 1983): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 1983): isTurningOnRadio()=false
D/BluetoothAdapterState( 1983): isTurningOffRadio()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1983): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1983): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1983): Handler(): got msg=1
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - Message: 1
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(19308080)( 1983): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1983): isTurningOnRadio()=false
D/BluetoothAdapterState( 1983): isTurningOffRadio()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1983): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1983): Deleted complete inbound failed shares, number = 0
,D/BluetoothAdapterService( 1983): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - Message: 1
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(19308080)( 1983): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1983): isTurningOnRadio()=false
D/BluetoothAdapterState( 1983): isTurningOffRadio()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1983): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1983): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1983): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - Message: 1
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(19308080)( 1983): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 1983): isTurningOnRadio()=false
D/BluetoothAdapterState( 1983): isTurningOffRadio()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1983): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1983): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 1983): new notify threadi!
V/BluetoothOppNotification( 1983): send delay message
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - Message: 1
D/BluetoothAdapterService(19308080)( 1983): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(19308080)( 1983): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 1983): isTurningOnRadio()=false
D/BluetoothAdapterState( 1983): isTurningOffRadio()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1983): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1983): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(19308080)( 1983): onProfileServiceStateChange() - All profile services started.
D/BluetoothAdapterState( 1983): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1983): enable
I/bt-btif ( 1983): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
V/OppService( 1983): ContentObserver received notification
E/bt-btu  ( 1983): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/OppService( 1983): ContentObserver received notification
V/BluetoothOppProvider( 1983): created cursor android.database.sqlite.SQLiteCursor@1a08fea2 on behalf of 
V/BluetoothOppProvider( 1983): created cursor android.database.sqlite.SQLiteCursor@26b5f733 on behalf of 
,I/GKI_LINUX( 1983): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 1983): btu_task pending for preload complete event
I/bt_hci_bdroid( 1983): init
I/bt_vendor( 1983): init
I/bt_vnd_conf( 1983): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
V/BluetoothOppProvider( 1983): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
I/bt_vnd_conf( 1983): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1983): libbt-hci init returns 0
,V/OppService( 1983): pendingUpdate is :  true
V/BluetoothOppProvider( 1983): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1983): created cursor android.database.sqlite.SQLiteCursor@113dfaf0 on behalf of 
V/BluetoothOppNotification( 1983): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 1983): created cursor android.database.sqlite.SQLiteCursor@3f792869 on behalf of 
V/BluetoothOppNotification( 1983): update too frequent, put in queue
V/BluetoothOppProvider( 1983): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/OppService( 1983): pendingUpdate is :  false
E/OppService( 1983): UpdateThread is Completed
V/BluetoothOppProvider( 1983): created cursor android.database.sqlite.SQLiteCursor@1b1c62ee on behalf of 
V/BluetoothOppNotification( 1983): outbound: succ-0  fail-0
I/NotificationManager( 1983): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
,V/BluetoothOppNotification( 1983): outbound notification was removed.
V/BluetoothOppProvider( 1983): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1983): created cursor android.database.sqlite.SQLiteCursor@234ed38f on behalf of 
V/BluetoothOppNotification( 1983): inbound: succ-0  fail-0
I/NotificationManager( 1983): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1983): inbound notification was removed.
V/BluetoothOppProvider( 1983): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1983): created cursor android.database.sqlite.SQLiteCursor@3c9fd61c on behalf of 
I/bt_userial_vendor( 1983): userial vendor open: opening /dev/ttyHS99
,D/bt_userial_vendor( 1983): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1983): device fd = 68 open
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
D/CAR.SERVICE( 5616): Connecting to CarCallService...
D/bt_hwcfg( 1983): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 1983): hw_config_cback state=1
I/art     ( 5616): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5616): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/bt_hwcfg( 1983): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 1983): hw_config_cback state=4
D/bt_hwcfg( 1983): Chipset Name: BCM4334B0
D/bt_hwcfg( 1983): Chipset BCM4334B0
D/bt_hwcfg( 1983): Target name = [BCM4334B0]
I/bt_hwcfg( 1983): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1983): hw_config_cback state=2
D/Tethering(  847): sendTetherStateChangedBroadcast 1, 0, 0
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1983): hw_config_cback state=3
I/bt_hwcfg( 1983): bt vendor lib: set UART baud 4000000
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  847): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/ResourcesManager( 5650): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5650): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5650): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5650): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5650): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NativeLibraryUtils( 5616): Install completed successfully. count=14 extracted=0
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 1983): hw_config_cback state=5
,E/wpa_supplicant( 5646): USIM:  scard_init function
I/wpa_supplicant( 5646): rfkill: Cannot open RFKILL control device
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 4
,I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 9
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 4
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CAR.SERVICE( 5616): com.google.android.projection.gearhead isn't installed.
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/IndexDatabaseHelper( 5650): Using schema version: 115
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/IndexDatabaseHelper( 5650): Index is fine
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/CAR.TEL.Service( 5616): Creating a new CarCallService.
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/CAR.TEL.PhoneAdapter( 5616): Creating a new PhoneAdapter instance
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
W/ActivityManager(  847): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5616): setListener: com.google.android.gms.car.dn@22d4d26d
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
W/ActivityManager(  847): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/CAR.TEL.PhoneAdapter( 5616): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5616): Starting CarCallService with initial phone null
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/wpa_supplicant( 5646): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/wpa_supplicant( 5646): wlan0: CTRL-EVENT-SCAN-STARTED 
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WifiStateMachine(  847): MAC Addr from driver = a0:39:f7:70:12:80
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  847): setPowerSaveActivated(false)
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/WifiServerServiceExt(  847): WIFI_STATE_CHANGED_ACTION [3]
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:00.499 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
E/WifiServerServiceExt(  847): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,I/WifiServerServiceExt(  847): batteryPsActivateMsgHandler : state:0 event:3
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
E/WifiConfigStore(  847): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WifiStateMachine(  847): enableVerboseLogging : level 2
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WifiStateMachine(  847): Setting OUI to DA-A1-19
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WifiNative-HAL(  847): Setting external_sim to 1
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/WifiNative-HAL(  847): startHal
E/wifi    (  847): getStaticLongField sWifiHalHandle 0x9abfb8ec
I/WifiHAL (  847): Initializing wifi
I/WifiHAL (  847): Creating socket
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/WifiHAL (  847): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  847): Did set static halHandle = 0xb065af80
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/wifi    (  847): halHandle = 0xb065af80, mVM = 0xb487c280, mCls = 0x400e06
E/wifi    (  847): getStaticLongField sWifiHalHandle 0x9abfb89c
D/wifi    (  847): array field set
I/WifiNative-HAL(  847): interface[0] = wlan0
I/WifiNative-HAL(  847): interface[1] = p2p0
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/wifi    (  847): setting scan oui 0x9da3bee0
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/WifiNative-HAL(  847): Waiting for HAL events mWifiHalHandle=-1335513216
D/wifi    (  847): waitForHalEvents called, vm = 0xb487c280, obj = 0x400e06, env = 0x9cc25eb0
E/wifi    (  847): getStaticLongField sWifiHalHandle 0x96faeb2c
D/WifiHAL (  847): Sending mac address OUI
E/WifiHAL (  847): failed to set scanning mac OUI; result = -95
D/WifiStateMachine(  847): Setting OUI to DA-A1-19
I/WifiNative-HAL(  847): startHal
D/wifi    (  847): setting scan oui 0x9da3bee0
D/WifiHAL (  847): Sending mac address OUI
E/WifiHAL (  847): failed to set scanning mac OUI; result = -95
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WfdsService( 1800): Supplicant Connection state is changed : true
,D/WfdsService( 1800): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1800): Set the WFDS Monitor: true
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WifiHS20(  847): hidePasspointNotification off =false
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WfdsMonitor( 1800): WfdsMonitorThread create
D/WfdsMonitor( 1800): WFDS Monitor is created and started
D/WfdsService( 1800): WiFi: Supplicant connection re-established
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/CAR.SERVICE( 5616): Package validated; name: com.android.vending
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:00.565 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/LGWifiP2pService(  847): P2pDisabledState{ when=-3ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
E/lowmemorykiller(  243): Error writing /proc/5305/oom_score_adj; errno=22
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Setting iface cfg
D/CommandListener(  274): Trying to bring up p2p0
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WifiScanningService(  847): SCAN_AVAILABLE : 3
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WifiScanningService(  847): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  847): startHal
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/RttService(  847): SCAN_AVAILABLE : 3
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/wifi    (  847): getting scan capabilities on interface[0] = 0x9da3bee0
D/WifiHAL (  847): Creating message to get scan capablities; iface = 24
D/wifi    (  847): failed to get capabilities : -95
E/WifiScanningService(  847): could not get scan capabilities
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WifiMonitor(  847): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService(  847): P2pEnablingState
D/LGWifiP2pService(  847): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2p socket connection successful
D/LGWifiP2pService(  847): P2pEnabledState
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/RttService(  847): DefaultState got{ when=-3ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
I/WifiServerServiceExt(  847): set CMD_ADD_DEFAULT_PROFILE
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/WifiServerServiceExt(  847): setWifiDualbandAPConnection band : 1
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/LGWifiP2pService(  847): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  847): before postfix = G3s-1
D/WifiServerServiceExt(  847): postfix byte check : 5
D/LGWifiP2pService(  847): after postfix = G3s-1
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WifiNative-HAL(  847): p2pGetDeviceAddress
D/WifiNative-HAL(  847): p2pGetDeviceAddress returning a2:39:f7:70:12:80
E/CtrlSupplicant( 1800): Access OK "@android:wpa_wlan0"
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WfdsService( 1800): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
E/CtrlSupplicant( 1800): Succeed to open control connection
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/LGWifiP2pService(  847): DeviceAddress: a2:39:f7:70:12:80
E/CtrlSupplicant( 1800): Succeed to open monitor connection
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WfdsMonitor( 1800): Supplicant connection established
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WfdsService( 1800): Connected to the supplicant for wfds
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WfdsService( 1800): Update P2p Interface State: 3
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,W/Settings( 5126): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/NotificationManager( 5616): com.google.android.gms: cancel(10436) by com.google.android.gms
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
E/wpa_supplicant( 5646): nWIFIDualbandAPConnection: 1
I/WifiServerServiceExt(  847): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 5646): disconnect_rssi_lvl: -100
D/LGWifiP2pService(  847): sending p2p persistent groups changed broadcast
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/WifiServerServiceExt(  847): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
E/wpa_supplicant( 5646): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/WifiServerServiceExt(  847): set CMD_UPDATE_DEFAULT_PROFILE
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/ActivityManager(  847): Process com.google.android.apps.plus (pid 5305) has died
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/LGWifiP2pService(  847): sending p2p connection changed broadcast
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WfdsService( 1800): WifiP2pState is changed : true
D/WfdsService( 1800): Receive the WFDS_ENABLE Method
D/WfdsService( 1800): Set the WFDS Monitor: true
D/WfdsService( 1800): Connected to the supplicant for wfds
D/WfdsJNI ( 1800): doCommand: WFDS_SET TRUE
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
I/wpa_supplicant( 5646): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/LGWifiP2pService(  847): InactiveState
I/wpa_supplicant( 5646): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsJNI ( 1800): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 5646): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt(  847): No p2p device connected
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WfdsService( 1800): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
V/BluetoothPbapReceiver( 1983): PbapReceiver onReceive 
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
V/BluetoothPbapReceiver( 1983): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1983): ***********state = 11
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WfdsService( 1800): isConnected: false
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1983): hw_config_cback state=6
D/LGWifiP2pService(  847): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WfdsService( 1800): GroupInfoAvailable: mGroupInfo is null
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1983): hw_config_cback state=6
I/wpa_supplicant( 5646): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1800): doCommand: WFDS_CLEAR_PD_INFO
I/wpa_supplicant( 5646): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WfdsJNI ( 1800): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WfdsJNI ( 1800): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WfdsService( 1800): selectPreferredScanChannel [6]
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/WfdsService( 1800): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
W/WfdsService( 1800): DefaultState - msg [9441285] is not handled
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
,D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1983): hw_config_cback state=6
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 1983): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:00.743 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/LocSvc_java(  847): onReceive
,I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:00.756 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 5646): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:00.759 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateASSOCIATING
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/NotificationManager( 4907): com.android.vending: cancel(10436) by com.android.vending
,D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateASSOCIATED
V/Finsky  ( 4907): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:00.791 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WiFiOffLoadUpdatePriority( 5650): remove : truetruetrue
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:00.797 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateFOUR_WAY_HANDSHAKE
D/GONS    ( 1746): GONS isTestMode: false Country: 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
,D/WiFiOffLoadUpdatePriority( 5650): remove1
V/WiFiOffLoadSharedPrefsUtils( 5650): save remove
,I/wpa_supplicant( 5646): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5646): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateGROUP_HANDSHAKE
I/WifiServiceExtension(  847): setVHTCapabilityType  : false
,D/WiFiOffLoadBroadcast( 5650): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5650): S: false, R: false
I/bt_hwcfg( 1983): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 1983): Settlement delay -- 100 ms
I/bt_hwcfg( 1983): Setting fw settlement delay to 100 
I/WifiServerServiceExt(  847): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  847): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  847): setSecurityType  : 2
,I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:00.867 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:00.873 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/WifiExtManager(  847): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@87e2c3b
D/ConnectivityService(  847): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  847): Got NetworkAgent Messenger
,D/ConnectivityService(  847): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  847): NetworkAgent connected
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
E/WifiConfigStore(  847): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  847): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Setting iface cfg
D/DhcpStateMachine(  847): StoppedState
E/WifiStateMachine(  847): Start Dhcp Watchdog 1
D/DhcpStateMachine(  847): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  847): WaitBeforeStartState
D/WiFiOffLoadUpdatePriority( 5650): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5650): connected SSID: null
,D/WiFiOffLoadUpdatePriority( 5650): private wpa: "NG700" 300
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1983): hw_config_cback state=2
I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
D/WifiServiceImplEx(  847): addOrUpdateNetwork pid=5650, uid=1000, packageName=android.uid.system:1000
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:00.948 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1983): hw_config_cback state=7
I/bt_hwcfg( 1983): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 1983): Setting local bd addr to F8:95:C7:87:85:54
E/addOrUpdateNetwork(  847):  uid = 1000 SSID "NG700" nid=0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
,D/ConnectivityService(  847): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/bt_hwcfg( 1983): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 1983): hw_config_cback state=8
I/bt_hwcfg( 1983): vendor lib fwcfg completed
I/bt-btif ( 1983): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 1983): btu_task received preload complete event
,I/        ( 1983): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 1983): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 1983): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 1983): BTE_InitTraceLevels -- TRC_PROTOCOL,0
,E/WifiStateMachine(  847): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  847): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b1956d2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b1956d2 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  847): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  847): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  847): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  847): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
E/WifiConfigStore(  847):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateCOMPLETED
E/WifiConfigStore(  847): Setting BSSID for "NG700"WPA_PSK to any
,D/WiFiOffLoadUpdatePriority( 5650):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5650): configuration updated: 0
I/WifiServerServiceExt(  847): set CMD_UPDATE_DEFAULT_PROFILE
I/art     ( 1728): Explicit concurrent mark sweep GC freed 29962(1778KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 13MB/22MB, paused 1.849ms total 91.346ms
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WiFiOffLoadUpdatePriority( 5650): configuration saved: true
V/BluetoothOppNotification( 1983): new notify threadi!
V/BluetoothOppNotification( 1983): send delay message
,V/BluetoothOppProvider( 1983): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
E/bt-btif ( 1983): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
V/BluetoothOppProvider( 1983): created cursor android.database.sqlite.SQLiteCursor@38f2e225 on behalf of 
V/BluetoothOppNotification( 1983): mUpdateCompleteNotification = true
I/GKI_LINUX( 1983): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 1983): warning : media task started media_task_refcnt 1 
V/BluetoothOppProvider( 1983): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
D/BT_PROF_AUDIO( 1983): created moving average (N=100)
D/BT_PROF_AUDIO( 1983): reset rate average
W/bt-btif ( 1983): overflow 0, enter 0, exit 0
E/bt-btif ( 1983): Calling BTA_HhEnable
E/bt-btif ( 1983): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 1983): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1983): Address is:F8:95:C7:87:85:54
,W/bt-smp  ( 1983): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1983): Plain text(LSB ~ MSB) = 1f 65 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1983): Encrypted text(LSB ~ MSB) = 87 fc 89 ff b9 8b 3b 62 de 48 b3 49 47 84 90 0c 
W/bt-btm  ( 1983): Stopping oneshot timer
V/BluetoothOppProvider( 1983): created cursor android.database.sqlite.SQLiteCursor@defbffa on behalf of 
V/BluetoothOppNotification( 1983): outbound: succ-0  fail-0
I/NotificationManager( 1983): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1983): outbound notification was removed.
V/BluetoothOppProvider( 1983): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1983): created cursor android.database.sqlite.SQLiteCursor@30ef19ab on behalf of 
V/BluetoothOppNotification( 1983): inbound: succ-0  fail-0
I/NotificationManager(  847): android: cancelAsUser(2) by android
I/NotificationManager( 1983): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1983): inbound notification was removed.
V/BluetoothOppProvider( 1983): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1983): created cursor android.database.sqlite.SQLiteCursor@34e23808 on behalf of 
I/ActivityManager(  847): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5716 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 95653088562; DSPS: 3225668; Offset : -2793759444
D/BluetoothAdapterProperties( 1983): Name is: G3s-1
,D/BluetoothManagerService(  847): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  847): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 1983): Scan Mode:20
D/BluetoothAdapterProperties( 1983): Discoverable Timeout:120
,E/bt-btif ( 1983): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 1983): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 1983): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 1983): BTA_JvEnable
E/bt-btif ( 1983): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 1983): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 1983): init_hci_slots(L136): in
D/IOP_DB_BT( 1983): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 1983): db_open: db_open : handle 2691172316l, read 11046 bytes onto local cache
D/IOP_DB_BT( 1983): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1983): db_query: result 1
I/        ( 1983): iop_db_open: iop_db_open status 0
E/bt-btif ( 1983): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 1983): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 1983): bta_pan_co_init
D/bte_conf( 1983): Device ID record 1 : primary
D/bte_conf( 1983):   vendorId            = 00c4
D/bte_conf( 1983):   vendorIdSource      = 0001
D/bte_conf( 1983):   product             = 13a1
D/bte_conf( 1983):   version             = 1000
D/bte_conf( 1983):   clientExecutableURL = 
D/bte_conf( 1983):   serviceDescription  = 
D/bte_conf( 1983):   documentationURL    = 
D/bte_conf( 1983): bte_load_did_conf no section named DID2.
I/bt-btif ( 1983): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 1983): btif_hf_upstreams_evt: wrong handle = 26465 
I/bt-btif ( 1983): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 1983): opc_state_cb(L140):  opc_state_cb state:0
D/BluetoothPermissionRequest( 5650): onReceive
D/BluetoothAdapterState( 1983): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1983): ScanMode =  20
D/BluetoothAdapterProperties( 1983): State =  11
D/BluetoothAdapterProperties( 1983): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 1983): Setting state to 12
I/BluetoothAdapterState( 1983): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(19308080)( 1983): updateAdapterState() - Broadcasting state to 1 receivers.
D/OppService( 1983): onOpcStateChange()
I/bt-btif ( 1983): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1983): ops_state_cb(L223):  ops_state_cb state:0
D/BluetoothManagerService(  847): Message: 60
D/BluetoothManagerService(  847): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/OppService( 1983): Recieved MESSAGE_OPC_ENABLE
D/BluetoothManagerService(  847): Broadcasting onBluetoothStateChange(true) to 6 receivers.
I/BluetoothAdapterState( 1983): Entering On State
D/LGBluetoothFeatureConfig( 1983): isPrivacyLogsEnabled : true
D/LGBluetoothFeatureConfig( 5650):  get() - isFeatureLoaded : false
D/OppService( 1983): onOpsStateChange() :0
I/BluetoothAdapterState( 1983): Entering On State from state = 11
I/bt-btif ( 1983): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1983): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1983): onFtpServerEnabled: /storage
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
D/BluetoothPanServiceJni( 1983): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/bt-btif ( 1983): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterService(19308080)( 1983): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(19308080)( 1983): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1983): [BTUI] autoConnect() : not allowed
D/OppService( 1983): Recieved MESSAGE_OPS_ENABLE
,D/LGBluetoothServiceAdapter( 1983): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1983): [BTUI]         global_name: G3s-1
D/BluetoothA2dp( 1983): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 1983): Scan Mode:21
D/LGBluetoothServiceAdapter( 1983): [BTUI]         local_name: G3s-1
I/bt-btif ( 1983): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1983): Discoverable Timeout:120
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
D/BluetoothAdapterService(19308080)( 1983): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(19308080)( 1983): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1983): [BTUI] autoConnect() : not allowed
D/DhcpStateMachine(  847): DHCPV4 request on wlan0
D/BluetoothHeadset(  847): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1746): onBluetoothStateChange: up=true
V/LgDhcpStateMachineHelper(  847): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  847): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/BluetoothHeadset( 1746): onBluetoothStateChange: up=true
D/BluetoothA2dp(  847): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1746): onBluetoothStateChange: up=true
E/BluetoothManagerService(  847): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  847): Bluetooth State Change Intent: 11 -> 12
D/bt_h4   ( 1983): vendor lib postload completed
,D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
D/LGBluetoothAPIService( 1800): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService(  847): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  847): Message: 40
D/BluetoothManagerService(  847): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
I/dhcpcd  ( 5731): version 5.5.6 starting
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
E/dhcpcd  ( 5731): get_duid: Read-only file system
I/BluetoothMapService( 1983): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1983): STATE_ON
,D/libc-netbsd( 4907): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4907): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4907): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4907): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1369): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
D/DSQN    (  847): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LGBluetoothAPIService( 1800): Message: 1
D/LGBluetoothAPIService( 1800): MESSAGE_BOOT_COMPLETED
I/LGBluetoothAPIService( 1800): [BTUI] LGBluetoothAPIService Binding Success
,D/BluetoothAdapterService( 1983): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1269e30
W/Finsky  ( 4907): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/BluetoothPbapService( 1983): Pbap Service onCreate
V/BluetoothPbapService( 1983): Starting PBAP service
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
D/LGBluetoothPbapAdapter( 1983): [BTUI] getInstance : create
V/BluetoothPbapService( 1983): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1983): state: 12
V/BluetoothMapService( 1983): Handler(): got msg=1
D/BluetoothMapMasInstance( 1983): Map Service startRfcommSocketListener
,D/LGBluetoothAPIServer( 1983): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1983): [BTUI] onBind()
V/BluetoothPbapService( 1983): Handler(): got msg=1
D/LGBluetoothAPIService( 1800): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1800): Message: 100
D/LGBluetoothAPIService( 1800): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  847): Message: 20
D/BluetoothManagerService(  847): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31d16391:true
V/BluetoothPbapService( 1983): Pbap Service startRfcommSocketListener
D/BluetoothMapMasInstance( 1983): MAS initSocket()
D/BluetoothMapMasInstance( 1983):   masId = 00
D/BluetoothMapMasInstance( 1983):   msgTypes = 0e
D/BluetoothMapMasInstance( 1983):   masName = SMS/MMS
D/BluetoothMapMasInstance( 1983):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 1983): getBluetoothService() called with no BluetoothManagerCallback
D/Finsky  ( 4907): [1] DailyHygiene.access$600: Logging device features
I/bt-btif ( 1983): BTA_JvCreateRecordByUser
I/bt-btif ( 1983): BTA_JvRfcommStartServer
V/BluetoothPbapService( 1983): Pbap Service initSocket
D/LGBluetoothServiceAdapter( 1983): [BTUI] createSocketChannel FD=83 mFd=0
V/BluetoothMapMasInstance( 1983): Succeed to create listening socket 
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothMapMasInstance( 1983): Accepting socket connection...
,W/BluetoothAdapter( 1983): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1983): BTA_JvCreateRecordByUser
D/LGBluetoothServiceAdapter( 1983): [BTUI] createSocketChannel FD=85 mFd=83
I/bt-btif ( 1983): BTA_JvRfcommStartServer
V/BluetoothPbapService( 1983): Succeed to create listening socket 
V/BluetoothPbapService( 1983): Accepting socket connection...
V/BluetoothSapReceiver( 1983): [BTUI] checkServiceStart
,V/AlarmManager(  847): RTC_WAKEUP set : Alarm{15a3c2f6 type 0 when 1454082601331 com.android.vending} when 1454082601331
D/LGBluetoothStateChangeReceiver( 1983): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
I/dhcpcd  ( 5731): wlan0: rebinding lease of 192.168.1.134
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 6
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/Finsky  ( 4907): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
I/ActivityManager(  847): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5749 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/PCSuite ( 5716): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/DeviceConnectionService( 1728): client connected with version: 8296000
,D/WearableService( 1728): callingUid 10006, callindPid: 1728
E/MDM     ( 1728): [102] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4965): Restart initialization of location
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4907): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/ResourcesManager( 5749): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
D/Finsky  ( 4907): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/UsbSettingsReceiver( 5650): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 5650): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5650): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5650): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5650): [AUTORUN] onReceive() : app userid = 0, current userid = 0
W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
,D/LGBluetoothProfileConnectionReceiver_EasySetting( 5749): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
D/AuthorizationBluetoothService( 1728): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WeatherService( 2659): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:50:1
,D/WeatherService( 2659): 2 : TimeTick Intent And Screen On
D/WeatherService( 2659): 2 : SDK version : 21
W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2659): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2659): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2659): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2659): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UsbSettingsControl( 5650): [AUTORUN] getUsbConnected() : connected=true
D/UpdateThreadPoolManager( 2659): 2 : This is isUpdating : false
D/WeatherService( 2659): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2659): 2 : buildUpdate, appWidgetId: 2
,D/WeatherTheme( 2659): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2659): 2 : Fixed theme : optimus
D/UsbSettingsReceiver( 5650): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5650): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5650): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5650): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5650): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 5650): [AUTORUN] setTetherStatus() : status=false
V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WeatherReflect( 2659): 2 : Map key string is -2
D/WiFiOffLoadBroadcast( 5650): MCCMNC not supported: null
D/PCSuite ( 5716): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/lim     ( 2659): 2 : time = 16:50
I/ActivityManager(  847): Killing 5186:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/WeatherReflect( 2659): Model Name : LG-D722
D/WeatherTheme( 2659): 2 : Different view - status_min_formatted : 49 != 50
D/WeatherTheme( 2659): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2659): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2659): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2659): currentPackage=com.lge.sizechangable.weather.theme.optimus
,W/System.err( 5165): android.os.DeadObjectException
,W/System.err( 5165): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5165): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5165): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5165): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5165): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5165): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5165): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5165): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5165): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5165): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5165): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5165): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5165): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5165): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5165): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5165): android.os.DeadObjectException
W/System.err( 5165): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5165): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5165): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5165): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5165): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5165): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5165): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5165): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5165): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5165): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5165): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5165): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5165): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5165): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5165): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
D/Weather4x2_optimus( 2659): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2659): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2659): forecast size is 0
,D/Theme   ( 2659): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2659): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2659): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2659): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2659): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2659): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2659): setTouchIntent, appWidgetId: 2
W/libprocessgroup(  847): failed to open /acct/uid_10089/pid_5186/cgroup.procs: No such file or directory
,W/ActivityManager(  847): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/Theme_WeatherAncestor_optimus( 2659): url is : null
I/ActivityManager(  847): Process com.google.android.talk (pid 5126) has died
,I/ActivityManager(  847): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5780 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 284us total 29.373ms
,D/Theme   ( 2659): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2659): 2 : update view, appWidgetId: 2
,D/WeatherService( 2659): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:50:1
I/art     (  307): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 22.935ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 22.525ms
,I/ActivityManager(  847): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5804 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ContextImpl( 5650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 1983): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1983): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1983): ***********state = 12
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
,D/LocalBluetoothProfileManager( 5650): Adding local A2DP profile
D/BluetoothManagerService(  847): Message: 30
,D/LocalBluetoothProfileManager( 5650): Adding local HEADSET profile
D/BluetoothManagerService(  847): Message: 30
D/UEI.SmartControl( 5780): Quickset Services start...
D/BluetoothManagerService(  847): Message: 30
,I/UEI.SmartControl( 5780): Manufacture = LGE
D/UEI.SmartControl( 5780): File observer start...
E/UEI.SmartControl( 5780): IR Port is disabled: false
D/UEI.SmartControl( 5780): Starting file observer...
D/UEI.SmartControl( 5780): Extracting JNI libs...
D/UEI.SmartControl( 5780): --- this system supports 32-bit or 64-bit only
D/BluetoothManagerService(  847): Message: 30
D/LocalBluetoothProfileManager( 5650): Adding local MAP profile
D/BluetoothMap( 5650): Create BluetoothMap proxy object
,D/BluetoothManagerService(  847): Message: 30
D/BluetoothManagerService(  847): Message: 30
V/BluetoothPbapService( 1983): Pbap Service onBind
D/LocalBluetoothProfileManager( 5650): LocalBluetoothProfileManager construction complete
,D/LGBluetoothUserBindClient( 5650): [BTUI] initUserBindClient
W/ContextImpl( 5650): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 5650): finishStartingService: stopping service
,D/BluetoothA2dp( 5650): Proxy object connected
D/A2dpProfile( 5650): Bluetooth service connected
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
D/BluetoothHeadset( 5650): Proxy object connected
D/HeadsetProfile( 5650): Bluetooth service connected
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
D/BluetoothInputDevice( 5650): Proxy object connected
D/HidProfile( 5650): Bluetooth service connected
,D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
D/BluetoothPan( 5650): BluetoothPAN Proxy object connected
D/PanProfile( 5650): Bluetooth service connected
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
D/BluetoothMap( 5650): Proxy object connected
D/MapProfile( 5650): Bluetooth service connected
D/BluetoothMap( 5650): getConnectedDevices()
D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
V/BluetoothMapService( 1983): getConnectedDevices()
D/BluetoothPbap( 5650): Proxy object connected
D/PbapServerProfile( 5650): Bluetooth service connected
D/LGBluetoothUserBindClient( 5650): [BTUI] onServiceConnected
,D/BluetoothPermissionRequest( 5650): onReceive
D/LGBluetoothFeatureConfig( 5650): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 5650): [BTUI] FileNotFound: readProperty
D/LGDMClient( 5804): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5804): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 5804): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/BluetoothOppReceiver( 1983): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
W/ContextImpl( 5804): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,V/BluetoothOppManager( 1983): restoreApplicationData! falsefalsenullnull
V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{2b3c7f1d type 2 when 96711 com.google.android.gms} when 96711
,V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothSapReceiver( 1983): [BTUI] checkServiceStart
D/UEI.SmartControl( 5780): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5780): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5780): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/LGBluetoothStateChangeReceiver( 1983): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,D/AuthorizationBluetoothService( 1728): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WiFiOffLoadBroadcast( 5650): MCCMNC not supported: null
D/LGDMClient( 5804): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 5804): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/PCSuite ( 5716): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 5716): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5716): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/LGDMClient( 5804): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/UEI.SmartControl( 5780): --- Selecting new region: 2
,I/UEI.SmartControl( 5780): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5780): Platform has CIR...
D/UEI.SmartControl( 5780): NO CIR support, need to check package...
I/UEI.SmartControl( 5780): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5780): QS Service created
I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  847): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5841 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,E/UEI.SmartControl( 5780): QS start get config
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/UEI.SmartControl( 5780): Loading JNI Libs...
D/ConnectivityService(  847): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/UEI.SmartControl( 5780):  configuring local db...
,I/dhcpcd  ( 5731): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5731): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  847): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/ActivityManager(  847): Process com.google.android.gms:car (pid 5616) has died
W/ActivityManager(  847): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,D/UEI.SmartControl( 5780):  ---- Has DB8: true
,D/UEI.SmartControl( 5780): QS start statue = true Error code = 0
,D/UEI.SmartControl( 5780): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5780): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
V/AudioFlinger(  278): thread 0xb56eb000 type 0 TID 1289 going to sleep
V/AudioFlinger(  278): thread 0xb5651000 type 0 TID 1288 going to sleep
V/AudioFlinger(  278): thread 0xb5735000 type 0 TID 1291 going to sleep
,D/UEI.SmartControl( 5780): IRRCDataComm has AudioManager!!!!.
I/art     (  847): Explicit concurrent mark sweep GC freed 50747(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 9.958ms total 232.518ms
,W/irrc_jni( 5780): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5780): IrrcClient ++ 
D/irrcClient( 5780): getIrrcService ++ 
D/irrcClient( 5780): getIrrcService -- 
D/irrcClient( 5780): IrrcClient -- 
W/irrc_jni( 5780): IRRCPlayer_nativeInit -- 
V/[BNRBootReceiver]( 5841): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/UEI.SmartControl( 5780): Services init done
D/BNRAndroBeam( 5841): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
I/UEI.SmartControl( 5780): Device manager: loading config....
D/UEI.SmartControl( 5780): QS Service init finished
D/UEI.SmartControl( 5780): QS Service version name: 0.1.73
,D/UEI.SmartControl( 5780): QS Service version code: 1073
D/UEI.SmartControl( 5780): Service requested: Control
D/UEI.SmartControl( 5780): Config is loaded...
V/[BNRBootReceiver]( 5841): Boot Receiver Return
,W/MainApplication( 5841): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5650): MCCMNC not supported: null
D/UEI.SmartControl( 5780):  ----- QS SDK is ready!!!
,D/UEI.SmartControl( 5780): Request IControl service: devices are loaded...
V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 5650): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5650): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5650): MCCMNC not supported: null
I/UEI.SmartControl( 5780): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5780): Internal service binding...
,V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/UEI.SmartControl( 5780): -----IControl: 11
D/UEI.SmartControl( 5780): Caller: com.lge.qremote
,D/UEI.SmartControl( 5780): ------------ IControl registerCallback...
D/WiFiOffLoadBroadcast( 5650): MCCMNC not supported: null
I/UEI.SmartControl( 5780): Registering callback...
D/UEI.SmartControl( 5780): -----IControl: 19
D/UEI.SmartControl( 5780): Caller: com.lge.qremote
I/UEI.SmartControl( 5780): Registering Services Ready callback...
I/UEI.SmartControl( 5780): Notify client services are ready...
D/UEI.SmartControl( 5780): -----IControl: 8
,D/UEI.SmartControl( 5780): Caller: com.lge.qremote
V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5650): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5650): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5650): MCCMNC not supported: null
D/PowerManagerServiceEx(  847): releaseWakeLockInternal: lock=559442643 [*alarm*], flags=0x0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=0
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/AudioManager( 5165): getMode name:com.lge.qremote
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/DSQN    (  847): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/Finsky  ( 4907): [589] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  847): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  847): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  847): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  847): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  847): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  847): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  847): bShouldSendDhcpAction Result: true
D/DhcpStateMachine(  847): DHCP Start/Renew wake lock is released.
D/LGWifiP2pService(  847): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  847): RunningState
I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5889 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/ConnectivityService(  847): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine(  847): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  847): ignoring duplicate network state non-change
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  847): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  847): Adding iface wlan0 to network 100
D/WifiHS20(  847): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  847): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine(  847): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
,E/ConnectivityService(  847): Unexpected mtu value: 0, wlan0
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
D/ConnectivityService(  847): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  847): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  847): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  847): addLocalRoutetoDefaultNetwork
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:03.122 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  847): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  847): Setting Dns servers for network 100 to [/192.168.1.1]
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:03.129 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/Nat464Xlat(  847): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  847): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  847): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  847): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  847):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  847):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Connected
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:03.135 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  847):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  847):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  847):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  847): currentScore = 0, newScore = 20
D/ConnectivityService(  847):    accepting network in place of null
D/ConnectivityService(  847): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
D/WIFI    (  847): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  847):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/TelephonyNetworkFactory-1( 1746): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:03.143 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/TelephonyNetworkFactory-1( 1746):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/NotificationManager(  847): android: cancelAsUser(2) by android
E/ConnectivityService(  847): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  847): Sending connecte,d broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] Start DNSResolver start to wait
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] wait 500ms before dns check
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/ConnectivityService(  847): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  847): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  847): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1835): |CORE| No family connected
I/QCNEJ   ( 1835): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/Tethering(  847): MasterInitialState.processMessage what=3
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=0
D/ConnectivityService(  847): validation of new default Network = false
D/ConnectivityService(  847): Default network via Wi-Fi connected. start DSQN
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/DSQN    (  847): enableDataServiceNotify 
D/DSQN    (  847): start dsqn bin
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
,I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1835): |CORE| sendDefaultNwMsg: default = 1
D/DSQN    (  847): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,V/NetworkPolicy(  847): [LG_RESTRICTED] checkMobilePolicy_type()
,I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
,D/libc-netbsd( 4907): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4907): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4907): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4907): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 4907): propertyValue:false
D/ConnectivityService(  847): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524290
I/DSQN    ( 5912): DSQN samuel.seo ver 141203
E/DSQN    ( 5912): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5912): created command queue thread
I/DSQN    ( 5912): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5912): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,W/ResourcesManager( 5889): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  847): Killing 5452:com.android.calendar/u0a13 (adj 15): empty #11
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] DNSResolver start dns
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  847): propertyValue:false
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 5912): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5912): restart monitoring
,I/DSQN    ( 5912): dsqn report finish
D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  847): DSQM DsqnNotification wlan0  1
D/DSQN    (  847): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 15:50:04 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454082603743], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454082603727]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Validated
D/ConnectivityService(  847): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  847): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  847):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  847):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  847): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  847): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524290
D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1746): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  847): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/libprocessgroup(  847): failed to open /acct/uid_10013/pid_5452/cgroup.procs: No such file or directory
D/WIFI    (  847):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1746):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/ActivityManager(  847): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5920 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/WifiDataContinuityService(  847): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  847): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/art     ( 5889): CheckpointMarkThreadRoots callback created = 0xaaf1c9b0
,I/Babel_SMS( 5889): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5889): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5889): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5889): MmsConfig.loadFromDatabase
I/art     ( 5889): CheckpointMarkThreadRoots callback created = 0xaaf1c990
I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 16:50:03.963 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
E/Babel_SMS( 5889): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5889): MmsConfig.loadFromResources
E/Babel_SMS( 5889): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5889): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,W/ResourcesManager( 5920): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5920): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SensorManager( 5889): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5889): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5889): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5889): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 5889): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5889): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5889): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5889): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5889): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5889): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5889): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5889): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5889): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5889): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5889): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5889): found sensor: Motion Accel, handle=46
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
I/MultiDex( 5920): VM with version 2.1.0 has multidex support
I/MultiDex( 5920): install
I/MultiDex( 5920): VM has multidex support, MultiDex support library is disabled.
,W/Settings( 5889): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5889): startup - clean
I/Babel   ( 5889): deleted: false for 0
,V/JNIHelp ( 5920): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AudioManager( 5165): getMode name:com.lge.qremote
,V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5650): MCCMNC not supported: null
W/AudioCapabilities( 5889): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5889): Unsupported mime audio/adpcm
W/AudioCapabilities( 5889): Unsupported mime audio/g726
W/AudioCapabilities( 5889): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5889): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5889): Unsupported mime video/mjpg
,W/VideoCapabilities( 5889): Unsupported mime video/theora
,V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5650): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5650): MCCMNC not supported: null
I/PCSuite ( 5716): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,W/ActivityThread( 5920): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5920): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7663866: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5920): Installed default security provider GmsCore_OpenSSL
D/PCSuite ( 5716): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/NotificationManager( 5920): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5920): com.google.android.gms: cancel(39789) by com.google.android.gms
V/WiFiOffLoadBroadcast( 5650): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5650): MCCMNC not supported: null
,I/PCSuite ( 5716): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5716): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 5889): Unsupported mime audio/evrc
,W/AudioCapabilities( 5889): Unsupported mime audio/qcelp
W/VideoCapabilities( 5889): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5889): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5889): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5889): Unsupported mime audio/evrc
D/ChimeraCfgMgr( 5920): Reading stored module config
W/VideoCapabilities( 5889): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5889): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5889): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5889): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5889): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5889): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  847): Process com.android.providers.calendar (pid 5402) has died
,I/AudioManager( 5165): getMode name:com.lge.qremote
D/ChimeraCfgMgr( 5920): Loading module com.google.android.gms.car from APK com.google.android.gms
I/vclib   ( 5889): onServiceConnected
W/Babel   ( 5889): Attempted to change video mute state without an active call.
I/NotificationManager( 5889): com.google.android.talk: cancel(10436) by com.google.android.talk
,E/MDM     ( 1728): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4965): Restart initialization of location
D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1728): No location to return for getLastLocation()
,W/FusedLocationProvider( 1728): location=null
D/CAR.SERVICE( 5920): Connecting to CarCallService...
,D/NativeLibraryUtils( 5920): Install completed successfully. count=14 extracted=0
,I/art     ( 5920): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5920): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 5920): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5920): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5920): Creating a new PhoneAdapter instance
W/ActivityManager(  847): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5920): setListener: com.google.android.gms.car.dn@22d4d26d
W/ActivityManager(  847): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5920): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5920): Starting CarCallService with initial phone null
I/ActivityManager(  847): Killing 5804:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_5804/cgroup.procs: No such file or directory
,I/NotificationManager( 5920): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 5920): mConnectedToCar = false, abort
,E/ActivityThread( 5920): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@a7521b5 that was originally bound here
E/ActivityThread( 5920): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@a7521b5 that was originally bound here
E/ActivityThread( 5920): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5920): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5920): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5920): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5920): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5920): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5920): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5920): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5920): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5920): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5920): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5920): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5920): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5920): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5920): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5920): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5920): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5920): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5920): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5920): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5920): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5920): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 5920): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3e5dba84 that was originally bound here
E/ActivityThread( 5920): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3e5dba84 that was originally bound here
E/ActivityThread( 5920): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5920): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5920): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5920): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5920): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5920): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5920): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5920): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5920): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5920): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5920): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5920): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5920): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5920): 	at android.app.ActivityThread.access,$1900(ActivityThread.java:155)
E/ActivityThread( 5920): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5920): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5920): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5920): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5920): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5920): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5920): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  847): Unbind failed: could not find connection for android.os.BinderProxy@3de85ea2
V/WifiInternetCheck(  847): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  847): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  847): onReceive
D/LocSvc_java(  847): got connectivity action
,I/ActivityManager(  847): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5968 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  847): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  847): Sending msg: 4 arg1:1 arg2:1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
D/LocSvc_java(  847): getAGpsConnectionInfo connType - 4
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,D/LocSvc_java(  847): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  847): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  847): Sending msg: 5 arg1:0 arg2:1
I/System.out(  847): propertyValue:false
I/System.out(  847): propertyValue:false
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkChangeNotifierAutoDetect( 1933): Network connectivity changed, type is: 2
,D/LocSvc_java(  847): NTP server returned: 1454082606607 (Fri Jan 29 16:50:06 GMT+01:00 2016) reference: 100771 certainty: 12 system time offset: 298
,D/AlarmManagerService(  847): Setting time of day to sec=1454082606
W/AlarmManagerService(  847): Unable to set rtc to 1454082606: Invalid argument
D/LocSvc_java(  847): Sending msg: 10 arg1:0 arg2:1
,I/ActivityManager(  847): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6002 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  847): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=6009 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/GpsLocationProvider(  847): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/[SystemUI]Clock( 1369): onReceive = android.intent.action.TIME_SET
D/WeatherService( 2659): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 16:50:6
I/LgeClockWidgetControlView( 1369): time changed, timezoneChanged : false
,D/WeatherService( 2659): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 2659): 2 : This is isUpdating : false
D/WeatherService( 2659): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2659): 2 : buildUpdate, appWidgetId: 2
W/ActivityManager(  847): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
D/WeatherTheme( 2659): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2659): 2 : Fixed theme : optimus
D/WeatherReflect( 2659): 2 : Map key string is -2
D/lim     ( 2659): 2 : time = 16:50
I/WeatherReflect( 2659): Model Name : LG-D722
D/WeatherTheme( 2659): 2 : exactly same view!
D/WeatherTheme( 2659): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/WeatherService( 2659): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 16:50:6
,I/[LGHome]LGDateChangeReceiver( 1874): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=29 currentDate=-1 dayofweek=6 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 1874): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 29
,I/ActivityManager(  847): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6039 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]LGCalendarIcon( 1874): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 29
,E/GpsLocationProvider(  847): No APN found to select.
W/ResourcesManager( 6002): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6002): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6002): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/LgeGpsConstants(  847): Can't find 'ext_gps.conf'!!
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/GoogleURLConnFactory( 1728): Using platform SSLCertificateSocketFactory
E/ActivityThread( 4965): Failed to find provider info for com.android.contacts.metadata
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out(  847): propertyValue:false
W/ResourcesManager( 6009): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6009): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6009): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  847): Process com.lge.bnr (pid 5841) has died
,I/MusicStore( 5968): Database version: 120
D/SyncManager(  847): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 37395, reason: UserStart, SyncResult: databaseError: true stats []
D/LgeGpsLocationProvider(  847): NTP server: europe.pool.ntp.org
,D/LgeGpsLocationProvider(  847): NTP server returned: 1454082607131 (Fri Jan 29 16:50:07 GMT+01:00 2016) reference: 101301 certainty: 33 system time offset: 3
D/SyncManager(  847): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 133150, reason: UserStart
I/PhenotypeConfigurator( 1728): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/NotificationManager(  847): android: cancelAsUser(716319171) by android
,I/AppConfig( 6002): Total System Memory = 906309632
,I/GalleryUtils( 6002): Application Heap = 96 MB
I/AppConfig( 6002): App Tier : NOT_DEF
,D/SystemHelper( 6002): region [EU], country [EU], operator [OPEN], sub-operator []
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ResourcesManager( 6039): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
I/ActivityManager(  847): Process com.lge.settings.easy (pid 5749) has died
W/ResourcesManager( 6039): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NotificationManager(  847): android: cancelAsUser(-1816247584) by android
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
I/LGEmail ( 6009): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/ContextImpl( 5968): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,D/LGEmail ( 6009): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/NotificationManager(  847): android: cancelAsUser(-1597574061) by android
,V/JNIHelp ( 6039): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Auth.Api.Credentials( 4965): [CredentialSyncAdapter] Unknown sync event.
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  847): propertyValue:false
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
W/System  ( 6039): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6039): Installed default security provider GmsCore_OpenSSL
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  847): propertyValue:false
,V/WifiInternetCheck(  847): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager(  847): Process com.android.vending (pid 4907) has died
,I/NotificationManager(  847): android: cancelAsUser(-591465577) by android
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
,I/NotificationManager(  847): android: cancelAsUser(-1816247584) by android
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 1728): propertyValue:false
,I/NotificationManager(  847): android: cancelAsUser(-1597574061) by android
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5968): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5968): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/ActivityManager(  847): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6099 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/art     ( 6039): Suspending all threads took: 39.819ms
,D/UEI.SmartControl( 5780): Internal timer expired: 1
,I/art     (  847): Explicit concurrent mark sweep GC freed 55917(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.311ms total 241.355ms
I/ActivityManager(  847): Process com.google.android.talk (pid 5889) has died
I/art     ( 6039): CheckpointMarkThreadRoots callback created = 0xb042da90
,W/ResourcesManager( 5968): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5968): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 6039): CheckpointMarkThreadRoots callback created = 0xb042da80
,E/YouTube MDX( 6039): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 6099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 5968): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  847): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6127 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6039): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,W/ResourcesManager( 6039): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6039): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/ConnectivityService(  847): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  847): dumpNetworkRequest
D/ConnectivityService(  847):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  847):     Requests:
D/ConnectivityService(  847):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847):     Lingered:
D/ConnectivityService(  847): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  847): apparently satisfied.  currentScore=60
D/ConnectivityService(  847): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 4965): CM callback handler got msg 524290
W/ActivityThread( 5968): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5968): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@feffdd9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5968): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5968): GMSCore installation verified
,I/ConfigStore( 5968): Config Database version: 1
,D/ALBootInit( 6127): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 6127): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 6127): [setNextAlert] start
,D/Alarms  ( 6127): [setNextAlert] (1)
,D/Alarms  ( 6127):  minTime  = 0
,D/Alarms  ( 6127):  -- OK multi -- 0
E/jeny.kim( 6127): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6127): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,I/CommonUtil( 6127): BUILD Operator: OPEN
,D/Alarms  ( 6127): broadcastToWidgetProvider : false
D/Alarms  ( 6127): Enter formatDayAndTime(final Context context, long timeInMiliSec)
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  847): Process com.android.settings (pid 5650) has died
,V/SettingsProvider(  847): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 6127): onReceive: android.intent.action.TIME_SET
,V/DigitalAppWidgetProvider( 6127): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3c3f9fe2
I/NotificationManager( 6039): com.google.android.youtube: cancel(2) by com.google.android.youtube
V/DigitalAppWidgetProvider( 6127): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3c3f9fe2
,I/dex2oat ( 6159): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-2125751352.jar --oat-fd=41 --oat-location=/data/data/com.google.android.youtube/cache/ads-2125751352.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/QuickCoverProvider( 6127): onReceiver
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6039): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6039): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6039): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
,W/PhenotypeConfigurator( 1728): Server returned 404
I/ActivityManager(  847): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6176 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 22.459ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 22.329ms
,W/InstanceID/Rpc( 6039): Found 10006
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.260ms
I/dex2oat ( 6159): dex2oat took 164.591ms (threads: 4)
,I/ActivityManager(  847): Process com.lge.sync (pid 5716) has died
,I/NotificationManager(  847): android: cancelAsUser(-591465577) by android
,W/ResourcesManager( 6176): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6039): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,D/CalendarApplication( 6176): CalendarApplication.onCreate()
,I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5526): 
,D/PreferenceKeysParser( 6176): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6176): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1f711e71, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@16d69456, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2b138cd7, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1186a9c4, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@fa830ad, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3c3f9fe2, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@149a1f73, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1269e30, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@ac42aa9, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@23bd82e, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@10ed3fcf, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@278f6d5c, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3c8bc865, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1b1493a, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@19a809eb, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@36540348, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@c7585e1, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@9dabf06, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1cfb59c7, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@234a0bf4, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@8e39f1d, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@10d3c592, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1149cb63, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@9f5f360, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@a201019, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@20e4a8de, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2683babf, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@37b6e58c, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@91894d5, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@e8e74ea, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@314343db, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@eb2ce78, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@25daa951, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@356f5b6, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2ba842b7, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2b825a24, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@19cf898d, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2954b742, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@27f45353, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@399cf490, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@11b83189, lg_preferences_recent_ti,mezones=com.android.calendar.adaptation.PreferenceKey$KeyData@37b058e, lg_
D/GeneralPreferenceUtils( 6176): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,D/Config  ( 6176): [init]
,I/Config  ( 6176): LGCalendar ver.4.40.17
I/Config  ( 6176): start check model
,I/Config  ( 6176): start check native_ca
I/Config  ( 6176): Config Operator=OPEN, Country=EU
D/Config  ( 6176): [setDefaultValuesToPref]
D/Config  ( 6176): [parseProfiles]
D/ProfilesParser( 6176): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6176): [debug_displayParseInfos] profile.operator = null
,D/Config  ( 6176): [updateProfiletoCountryInfo]
D/GeneralPreference( 6176): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6176): [updateWidgets] 
,I/InitNotificationRingtoneService( 6176): Start InitializeAlertRingtoneService.onHandleIntent
I/GoogleURLConnFactory( 4965): Using platform SSLCertificateSocketFactory
,I/AlertUtils( 6176): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 6176): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/MediaRouter( 5968): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,V/MusicLeanback( 5968): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  274): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/NetworkMonitor( 5968): type=WIFI subType= reason=null isConnected=true
I/AlertUtils( 6176): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6176): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 6039): propertyValue:false
D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  847): Process com.lge.qremote (pid 5165) has died
D/UEI.SmartControl( 5780): Service.onUnbind: IControl
D/UEI.SmartControl( 5780): Service.onDestroy
,D/UEI.SmartControl( 5780): Shutdown IRRCPlayer... 
I/PhoneApp( 1746): onTrimMemory: 10
I/PhoneApp( 1746): trim memory
,I/AlertUtils( 6176): set default noti to content://media/internal/audio/media/38
I/rmt_storage(  269): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  269): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  269): wakelock acquired: 1, error no: 42
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/InitNotificationRingtoneService( 6176): End InitializeAlertRingtoneService.onHandleIntent
I/BackgroundMemoryTrimmer( 1933): Trimming objects from memory, since app is in the background.
,D/ChimeraCfgMgr( 4965): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4965): Module APK com.google.android.play.games already loaded
I/NotificationManager( 6039): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,W/DriveInitializer( 4965): Awaiting to be initialized
,W/DriveInitializer( 4965): Background init thread started
I/art     ( 4868): Explicit concurrent mark sweep GC freed 2064(78KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 790us total 84.677ms
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  269): 
,I/rmt_storage(  269): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/irrc_jni( 5780): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5780): ~IrrcClient ++ 
D/irrcClient( 5780): ~IrrcClient -- 
W/irrc_jni( 5780): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5780): Blaster closed
D/UEI.SmartControl( 5780): Blaster closed
D/UEI.SmartControl( 5780): Shut down QS...
,D/UEI.SmartControl( 5780): Stopped file observer...
I/UEI.SmartControl( 5780): QS lib stop result = true
,D/UEI.SmartControl( 5780): QS shutdown complete
I/NetworkMonitor( 5968): type=WIFI subType= reason=null isConnected=true
,W/art     ( 6099): Attempt to remove local handle scope entry from IRT, ignoring
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4965): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,I/GHttpClientFactory( 5968): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/eas_req ( 6009): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/GoogleURLConnFactory( 5968): Using platform SSLCertificateSocketFactory
W/HolidayIntentService( 6176): onHandleIntent
D/MonthWidgetProvider( 6176): [onReceive]
D/CalendarWidgetProvider( 6176): [onReceive]
,D/CalendarWidgetProvider( 6176): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/HolidayDataLoader( 6176): readJsonAsset : holiday.json
D/CalendarTypeController( 6176): [onUpdateAndInitCalendarTime]
W/DriveInitializer( 4965): Background init thread ended
,D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/HolidayIntentService( 6176): onHandleIntent:holiday data empty
,I/ActivityManager(  847): Process com.uei.lg.quicksetsdk.lite (pid 5780) has died
,I/PhoneApp( 1746): onTrimMemory: 15
I/PhoneApp( 1746): trim memory
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WeekWidgetProvider( 6176): [onReceive]
D/CalendarWidgetProvider( 6176): [onReceive]
D/CalendarWidgetProvider( 6176): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6176): [onUpdateAndInitCalendarTime]
D/WeatherAncestor( 2659): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 16:50:10
I/NotificationManager(  847): android: cancelAsUser(2) by android
D/UpdateThreadPoolManager( 2659): 2 : This is isUpdating : false
,I/GamesSyncServiceMain( 4965): Found unexpected GCM tag when scheduling; aborting
D/Weather_cast( 2659): 2 : set auto-update time : 1/29 19:50
I/art     ( 6099): CheckpointMarkThreadRoots callback created = 0xb042d7b0
W/GamesSyncServiceMain( 4965): Failed to execute periodic sync, missing client context - aborting
,D/WeatherAncestor( 2659): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 16:50:10
D/WeatherService( 2659): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
,D/libc-netbsd( 6099): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6099): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  274): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  274): App 10086 tries DNS query. Accept family:2 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
,D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  847): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6265 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/art     ( 6099): CheckpointMarkThreadRoots callback created = 0xb042d790
W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2659): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2659): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2659): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  847): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6284 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/NotificationManager( 5968): com.google.android.music: cancel(1061) by com.google.android.music
,D/libc-netbsd( 4965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
,D/TimeService( 6265): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454082610503
D/        ( 6265): TimeServiceNative: User Time to be set is 1454082610503
D/QC-time-services( 6265): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6265): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6265): Lib:time_genoff_operation: pargs->ts_val = 1454082610503
D/QC-time-services( 6265): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  322): Daemon: Connection accepted:time_genoff
D/QC-time-services(  322): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454082610503
D/QC-time-services(  322): Daemon:genoff_opr: Base = 2, val = 1454082610503, operation = 0
D/QC-time-services(  322): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/11/70 19:51:42
D/QC-time-services(  322): Daemon:Value read from RTC seconds = 13981902000
D/QC-time-services(  322): Daemon:new time 1454082610503 
D/QC-time-services(  322): Daemon: delta 1440100708503 genoff 1440100708503 
D/QC-time-services(  322): Daemon:genoff_persistent_update: Writing genoff = 1440100708503 to memory
D/QC-time-services(  322): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  322): Daemon:time_persistent_memory_opr:Genoff write operation 
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 4965): propertyValue:false
D/QC-time-services(  322): Updating the TOD offset
D/QC-time-services(  322): Daemon:genoff_persistent_update: Writing genoff = 1440100708503 to memory
D/QC-time-services(  322): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  322): Daemon:time_persistent_memory_opr:Genoff write operation 
I/HubEmail( 6009): JNI_OnLoad()
I/HubEmail( 6009): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6009): registerNatives()
I/HubEmail( 6009): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6009): registerNativeMethods()
I/HubEmail( 6009): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6009): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,E/QC-time-services(  322): Daemon:Update to modem bit set
D/QC-time-services(  322): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  322): Daemon: Base = 2, Value being sent to MODEM = 1124135908503
E/QC-time-services( 6265): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  322): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  322): Daemon: Time-services: Waiting to acceptconnection
,I/NotificationManager(  847): android: cancelAsUser(353845882) by android
W/Settings( 6009): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/CheckinService( 4965): Checkin interval check for package: unspecified last checkin: 1454063372312 min interval config: 0 actual interval: 19238267
,I/art     (  847): Explicit concurrent mark sweep GC freed 22047(1072KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 3.447ms total 193.057ms
,I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5526): 
,I/ActivityManager(  847): Process com.google.android.gms:car (pid 5920) has died
,D/libc-netbsd( 4965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LGDMClient( 6284): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6284): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6284): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6284): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6284): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6284): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6284): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6316 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/LGDMClient( 6284): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5526): 
,I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5526): 
W/ContextImpl( 6284): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6284): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6284): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6284): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6284): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6284): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  274): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  274): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
I/System.out( 6039): propertyValue:false
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/System.out( 6039): propertyValue:false
D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/AppUp4:AppBoxCP( 6316): onCreate
,W/AppUp4:DB( 6316):  [AppBoxDatabaseHelper] construct
I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5526): 
I/AppUp4:DB( 6316):  setFingerPrint start
I/AppUp4:DB( 6316):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6316):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6316):  SDK version = 0
I/AppUp4:DB( 6316):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6316): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6316): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6316): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6316): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6316): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6316): onReceive
I/AppUp4:CustModeStarterReceiver( 6316): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6316): Context : android.app.ReceiverRestrictedContext@fa830ad
D/AppUp4:CustFacade( 6316): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6316): isSimDevice : true
,I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5526): 
D/AppUp4:CustModeStarterReceiver( 6316): begin check event
I/AppUp4:CustModeStarterReceiver( 6316): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6316): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6316): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6316): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6316): handleAsyncCustNotification do not startCustService
I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5526): 
,I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5526): 
I/LgeMiscReceiver( 3118): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3118): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3118): networkInfo.isConnected() = true
D/PhoneState( 3118): setPdpRejectCasuse : false
D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,I/ActivityManager(  847): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6338 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  847): Process com.lge.clock (pid 6127) has died
,D/PhoneMonitor( 6338): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6338): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6338): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 4965): Checkin interval check for package: unspecified last checkin: 1454063372312 min interval config: 0 actual interval: 19239115
V/DownloadManager( 3141): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3141): DownloadService onCreate
,I/DownloadManager( 3141): in removeSpuriousFiles
D/PhoneMonitor( 6338): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/NotificationManager( 3141): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/TelephonyAutoProfiling( 6338): [loadFeatureFromXml] *** start feature loading from xml
V/DownloadManager( 3141): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3141): created cursor android.database.sqlite.SQLiteCursor@399cf490 on behalf of 3141
,D/TelephonyAutoProfiling( 6338): [parse] Load xml
I/ActivityManager(  847): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6362 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/TelephonyAutoProfiling( 6338): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6338): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/DownloadManager( 3141): DownloadService onStartCommand
,I/DownloadManager( 3141): in trimDatabase
V/DownloadManager( 3141): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3141): created cursor android.database.sqlite.SQLiteCursor@10e6d1af on behalf of 3141
,D/PhoneMonitor( 6338): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3141): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3141): created cursor android.database.sqlite.SQLiteCursor@2284c9bc on behalf of 3141
,V/DownloadManager( 3141): DownloadService onDestroy
I/art     ( 4965): Explicit concurrent mark sweep GC freed 20928(1507KB) AllocSpace objects, 35(583KB) LOS objects, 39% free, 14MB/23MB, paused 1.739ms total 165.571ms
,I/CheckinService( 4965): Disabling old GoogleServicesFramework version
,D/DrmBroadcastReceiver( 6362): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6362): 1  network is available. Sync DRM Time with NTP
I/NotificationManager( 6099): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
V/DrmService( 6362): Service onCreate
D/DrmService( 6362): Received new request = 2
D/WeatherAncestor( 2659): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:50:11
D/UpdateThreadPoolManager( 2659): 2 : This is isUpdating : false
,D/WeatherAncestor( 2659): connectivity changed - connection : true
D/Weather_cast( 2659): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2659): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:50:11
D/WeatherService( 2659): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/DrmSntpClient( 6362): Start Sync process
D/DrmSntpClient( 6362): Server : 0
,D/libc-netbsd( 6362): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6362): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6362): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6362): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  274): App 10051 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6384 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2659): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2659): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2659): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/CheckinService( 4965): Checking schedule, now: 1454082611788 next: 1454063402265
I/CheckinService( 4965): active receiver: enabled
,I/CheckinService( 4965): Preparing to send checkin request
,I/EventLogService( 4965): Accumulating logs since 1454082395234
I/NotificationManager(  847): android: cancelAsUser(2145784878) by android
,I/NotificationManager(  847): android: cancelAsUser(2126026182) by android
,I/ActivityManager(  847): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6403 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6384): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationManager(  847): android: cancelAsUser(353845882) by android
,I/ActivityManager(  847): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=6424 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  847): Process com.google.android.music:main (pid 5968) has died
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/CheckinRequestBuilder( 4965): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4965): Failed to find provider info for com.google.android.wearable.settings
,I/Gmail   ( 6403): getAccountsCursor
W/GAV2    ( 6403): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6403): Error finding the version of the Email provider.....
E/Gmail   ( 6403): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6403): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6403): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6403): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6403): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6403): We do not support migrating this version of the Email provider.
W/Gmail   ( 6403): Sync started for account: account:61035162
,I/Gmail   ( 6403): getAccountsCursor
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6424): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/Babel_SMS( 6384): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6384): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6384): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6384): MmsConfig.loadFromDatabase
I/GAv4    ( 6424): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6424):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6424):   adb logcat -s GAv4
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6424): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6424): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/VacuumService( 1728): Vacuum at: now=1454082612800 tag=VacuumService
,W/GAv4    ( 6424): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/Babel_SMS( 6384): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6384): MmsConfig.loadFromResources
E/Babel_SMS( 6384): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6384): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 6424): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6424): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6424): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  847): Process com.lge.email (pid 6009) has died
,W/ActivityManager(  847): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/SensorManager( 6384): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6384): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6384): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6384): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6384): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6384): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6384): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6384): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6384): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6384): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6384): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6384): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6384): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6384): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6384): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6384): found sensor: Motion Accel, handle=46
I/art     ( 6384): CheckpointMarkThreadRoots callback created = 0xaaf397d0
,I/art     ( 6384): CheckpointMarkThreadRoots callback created = 0xaaf397b0
,I/art     (  847): Explicit concurrent mark sweep GC freed 23953(1159KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.883ms total 226.129ms
,W/Settings( 6384): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Gmail   ( 6403): Observing account changes for notifications
W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Babel_Crash( 6384): startup - clean
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 6362): propertyValue:false
,I/Babel   ( 6384): deleted: false for 0
,I/LGDrmClient( 6362): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  286): eDRM_SetDRMTime +++
I/LGDRM   (  286): [DRM] SET TIME : YR=2016, MON=1, DAY=29
,I/LGDRM   (  286): [DRM] SET TIME : HR=15, MIN=50, SEC=13
V/ILGDrmService(  286): eDRM_SetDRMTime ---
,I/DrmSntpClient( 6362): Synched
D/DrmService( 6362): Completed !! request = 2
D/DrmService( 6362): Request count = 0
V/DrmService( 6362): Service onDestroy
I/WebViewFactory( 6424): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/Gmail   ( 6403): notifyAccountChanged
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,I/Gmail   ( 6403): getAccountsCursor
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
I/Gmail   ( 6403): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/AudioCapabilities( 6384): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6384): Unsupported mime audio/adpcm
I/Gmail   ( 6403): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/AudioCapabilities( 6384): Unsupported mime audio/g726
W/AudioCapabilities( 6384): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6384): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6384): Unsupported mime video/mjpg
W/VideoCapabilities( 6384): Unsupported mime video/theora
,I/LibraryLoader( 6424): Time to load native libraries: 11 ms (timestamps 7651-7662)
,I/LibraryLoader( 6424): Expected native library version number "",actual native library version number ""
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Gmail   ( 6403): notifyAccountChanged
W/AudioCapabilities( 6384): Unsupported mime audio/evrc
V/WebViewChromiumFactoryProvider( 6424): Binding Chromium to main looper Looper (main, tid 1) {16e38716}
W/AudioCapabilities( 6384): Unsupported mime audio/qcelp
I/LibraryLoader( 6424): Expected native library version number "",actual native library version number ""
W/VideoCapabilities( 6384): Unrecognized profile 2130706433 for video/avc
I/chromium( 6424): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/Gmail   ( 6403): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/AudioCapabilities( 6384): Unsupported mime audio/amr-wb-plus
I/Gmail   ( 6403): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/AudioCapabilities( 6384): Unsupported mime audio/qcelp
,I/BrowserStartupController( 6424): Initializing chromium process, singleProcess=true
W/art     ( 6424): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6424): ApplicationContext is null in ApplicationStatus
W/AudioCapabilities( 6384): Unsupported mime audio/evrc
,W/VideoCapabilities( 6384): Unsupported mime video/mp4v-esdp
,W/chromium( 6424): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6424): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6424): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6424): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6424): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6424): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6424): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6424): Remote Branch: 
I/Adreno-EGL( 6424): Local Patches: 
I/Adreno-EGL( 6424): Reconstruct Branch: 
I/VideoCapabilities( 6384): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6384): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6384): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6384): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6384): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6384): onServiceConnected
W/Babel   ( 6384): Attempted to change video mute state without an active call.
,D/libc-netbsd( 6384): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6384): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6384): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6384): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6384): propertyValue:false
I/NotificationManager( 6384): com.google.android.talk: cancel(10436) by com.google.android.talk
I/Babel   ( 6384): connection state changed from UNKNOWN to CONNECTED
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/AudioPolicyService(  278): registerClient() client 0xb3826ac0, uid 10079
,W/AudioManagerAndroid( 6424): Requires BLUETOOTH permission
I/ActivityManager(  847): Process com.android.calendar (pid 6176) has died
,I/NSApplication( 6424): Starting up...
,I/Gmail   ( 6403): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15845, normalSync: true
I/SyncAdapterService( 6424): Ignoring sync request for non-current account
,I/art     ( 4868): Explicit concurrent mark sweep GC freed 2953(118KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 451us total 63.055ms
,I/ActivityManager(  847): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6531 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Gmail   ( 6403): getAccountsCursor
,I/NotificationManager(  847): android: cancelAsUser(-701419433) by android
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6403): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6403): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NotificationManager(  847): android: cancelAsUser(2) by android
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,V/JNIHelp ( 6403): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  847): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6557 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/System  ( 6403): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6403): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  847): Killing 6002:com.android.gallery3d/u0a23 (adj 15): empty #11
W/ResourcesManager( 6557): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6557): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
I/MultiDex( 6557): VM with version 2.1.0 has multidex support
I/MultiDex( 6557): install
,I/MultiDex( 6557): VM has multidex support, MultiDex support library is disabled.
W/libprocessgroup(  847): failed to open /acct/uid_10023/pid_6002/cgroup.procs: No such file or directory
,I/NotificationManager(  847): android: cancelAsUser(2) by android
,V/JNIHelp ( 6557): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 6557): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6557): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7663866: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6557): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6557): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6557): com.google.android.gms: cancel(39789) by com.google.android.gms
I/iu.SyncManager( 4965): SYNC; picasa accounts
,I/art     ( 6557): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6557): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/NetworkLogImpl( 4965): Loaded NetworkSpeedPredictor
I/iu.Environment( 4965): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/libc-netbsd( 6403): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6403): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6403): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6403): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10053
D/DnsProxyListener(  274): App 10053 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
I/iu.UploadsManager( 4965): num queued entries: 0
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/iu.UploadsManager( 4965): num updated entries: 0
I/iu.SyncManager( 4965): NEXT; no task
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 1728): propertyValue:false
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6403): propertyValue:false
D/libc-netbsd( 6403): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6403): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  847): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6586 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NativeLibraryUtils( 6557): Install completed successfully. count=14 extracted=0
,I/NotificationManager(  847): android: cancelAsUser(-1874035846) by android
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 316us total 26.866ms
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 343us total 22.206ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 21.295ms
,I/art     ( 6403): CheckpointMarkThreadRoots callback created = 0xaaf04360
I/ActivityManager(  847): Process com.lge.appbox.client (pid 6316) has died
,I/GCM     ( 1728): GCM config loaded
,I/art     ( 6403): CheckpointMarkThreadRoots callback created = 0xb053ab90
D/WVCdm   (  278): Instantiating CDM.
I/WVCdm   (  278): CdmEngine::OpenSession
I/WVCdm   (  278): Level3 Library Dec 11 2014 16:13:16
,I/NotificationManager(  847): android: cancelAsUser(1500439826) by android
,W/WVCdm   (  278): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  278): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  278): L1 library not specified. Falling Back to L3
I/ActivityManager(  847): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=6610 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GoogleURLConnFactory( 6557): Using platform SSLCertificateSocketFactory
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=3867498432
,I/DigitalAppWidgetProvider( 6586): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2659): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 16:50:15
D/UpdateThreadPoolManager( 2659): 2 : This is isUpdating : false
D/Weather_cast( 2659): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2659): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 16:50:15
,D/WeatherService( 2659): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
I/ActivityManager(  847): Killing 6265:com.qualcomm.timeservice/1000 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_6265/cgroup.procs: No such file or directory
,W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2659): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2659): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2659): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/libc-netbsd( 6557): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6557): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6557): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6557): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6557): propertyValue:false
I/MusicStore( 6610): Database version: 120
,D/libc-netbsd( 6403): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6403): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6610): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/WearableService( 1728): callingUid 10006, callindPid: 1728
,E/MDM     ( 1728): [133] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/art     (  847): Explicit concurrent mark sweep GC freed 29019(1343KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.443ms total 158.573ms
I/art     (  847): WaitForGcToComplete blocked for 6.546ms for cause HeapTrim
,D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4965): Restart initialization of location
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd( 6557): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6557): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6557): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6557): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6610): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6610): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  847): Process com.google.android.setupwizard (pid 6338) has died
,I/ActivityManager(  847): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6644 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  847): RTC_WAKEUP set : Alarm{3dd951a type 0 when 1454082615777 com.android.vending} when 1454082615777
,I/art     ( 6557): CheckpointMarkThreadRoots callback created = 0xb042dc40
,W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
,I/art     ( 6557): CheckpointMarkThreadRoots callback created = 0xb042dc30
,W/ResourcesManager( 6610): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6610): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6610): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/art     ( 6384): Suspending all threads took: 77.448ms
,W/ActivityThread( 6610): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6610): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@feffdd9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6610): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6610): GMSCore installation verified
I/ConfigStore( 6610): Config Database version: 1
,I/art     ( 1728): Explicit concurrent mark sweep GC freed 80383(4MB) AllocSpace objects, 37(615KB) LOS objects, 40% free, 13MB/23MB, paused 2.230ms total 142.726ms
,I/MediaRouter( 6610): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/dex2oat ( 6664): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/the.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/opt/the.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/NotificationManager( 6403): com.google.android.gm: cancel(10436) by com.google.android.gm
,I/GHttpClientFactory( 6610): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6610): Using platform SSLCertificateSocketFactory
I/dex2oat ( 6664): dex2oat took 144.040ms (threads: 4)
D/Finsky  ( 6644): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/NetworkMonitor( 6610): type=WIFI subType= reason=null isConnected=true
,I/MusicLifecycle( 6610): Sync started
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NetworkMonitor( 6610): type=WIFI subType= reason=null isConnected=true
I/art     ( 6610): CheckpointMarkThreadRoots callback created = 0xb042d3e0
,I/GHttpClientFactory( 6610): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6610): Using platform SSLCertificateSocketFactory
I/art     ( 6610): CheckpointMarkThreadRoots callback created = 0xb042d3a0
,I/ActivityManager(  847): Process com.lge.lgdmsclient (pid 6284) has died
,W/ContextImpl( 3373): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/NotificationManager( 6610): com.google.android.music: cancel(1061) by com.google.android.music
,D/Finsky  ( 6644): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dex2oat ( 6702): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=37 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/Settings( 6644): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6644): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6644): com.android.vending: cancel(-1050172287) by com.android.vending
,I/dex2oat ( 6702): dex2oat took 84.187ms (threads: 4)
I/Adreno-EGL( 6557): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6557): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6557): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6557): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6557): Remote Branch: 
I/Adreno-EGL( 6557): Local Patches: 
I/Adreno-EGL( 6557): Reconstruct Branch: 
,D/Finsky  ( 6644): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6644): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6644): Skipping gmscore version check
,I/Adreno-EGL( 6557): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6557): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6557): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6557): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6557): Remote Branch: 
I/Adreno-EGL( 6557): Local Patches: 
I/Adreno-EGL( 6557): Reconstruct Branch: 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/DownloadManager( 3141): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3141): created cursor android.database.sqlite.SQLiteCursor@3ea5ec9a on behalf of 6644
D/Finsky  ( 6644): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/GAV2    ( 6403): Thread[GAThread,5,main]: No campaign data found.
D/Finsky  ( 6644): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/WVCdm   (  278): CdmEngine::CloseSession
,I/WVCdm   (  278): L3 Terminate.
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  847): android: cancelAsUser(2) by android
,D/libc-netbsd( 6610): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6610): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6610): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6610): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10081
D/DnsProxyListener(  274): App 10081 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 6610): propertyValue:false
D/libc-netbsd( 6610): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6610): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/Finsky  ( 6644): [800] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6644): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     ( 6403): Explicit concurrent mark sweep GC freed 76719(2MB) AllocSpace objects, 0(0B) LOS objects, 24% free, 10MB/14MB, paused 649us total 60.085ms
,I/Gmail   ( 6403): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15917, normalSync: true
,I/Gmail   ( 6403): lowestBackward conversation id 0
D/libc-netbsd( 6610): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6610): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/WVCdm   (  278): CdmEngine::OpenSession
I/WVCdm   (  278): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  278): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  278): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  278): L1 library not specified. Falling Back to L3
,I/NotificationManager( 6403): com.google.android.gm: cancel(10436) by com.google.android.gm
,I/NotificationManager( 6403): com.google.android.gm: cancel(10436) by com.google.android.gm
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=1675684545
I/Gmail   ( 6403): notifyAccountChanged
,I/Gmail   ( 6403): getAccountsCursor
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6403): notifyAccountChanged
,W/Gmail   ( 6403): Sync complete for account: account:61035162
I/Gmail   ( 6403): getAccountsCursor
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  847): android: cancelAsUser(1479798955) by android
,W/BaseAppContext( 4965): Using Auth Proxy for data requests.
W/BaseAppContext( 4965): Using Auth Proxy for data requests.
,I/art     ( 4868): Explicit concurrent mark sweep GC freed 3181(124KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 830us total 30.090ms
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  847): Process com.google.android.apps.magazines (pid 6424) has died
,W/BaseAppContext( 4965): Using Auth Proxy for data requests.
I/MusicSyncAdapter( 6610): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 6610): Periodic update
,W/BaseAppContext( 4965): Using Auth Proxy for data requests.
,W/BaseAppContext( 4965): Using Auth Proxy for data requests.
W/BaseAppContext( 4965): Using Auth Proxy for data requests.
,W/BaseAppContext( 4965): Using Auth Proxy for data requests.
,W/MusicApiClient( 6610): Activity events list is null or empty. Skip reporting.
,I/MusicLifecycle( 6610): Sync ended
,I/NotificationManager(  847): android: cancelAsUser(-1123058983) by android
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6610): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  847): Start proc com.lge.qmemoplus for service com.lge.qmemoplus/.network.googledrive.DriveSyncService: pid=6740 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/NotificationManager(  847): android: cancelAsUser(-379682945) by android
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6610): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
I/MusicLeanback( 6610): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6610): Stop autocaching.
,W/ResourcesManager( 6740): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/art     (  847): Explicit concurrent mark sweep GC freed 24986(1067KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 7.359ms total 176.029ms
,E/App     ( 6740): [App][onCreate()] 4.40.23
I/Icing   ( 4965): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6610): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
E/GmsUtils( 6610): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6610): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/Icing   ( 4965): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/AccountManager( 6740): setSyncFrequency
,I/ActivityManager(  847): Process com.android.chrome (pid 6531) has died
W/BaseAppContext( 1728): Using Auth Proxy for data requests.
,D/DriveSyncService( 6740): onCreate
,D/DriveSyncService( 6740): onBind
D/DriveSyncAdapter( 6740): onPerformSync() START
D/DriveSyncAdapter( 6740): Not added account. Stop
I/NotificationManager(  847): android: cancelAsUser(1312559638) by android
E/BaseAppContext( 1728): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/ActivityManager(  847): Process com.google.android.youtube (pid 6039) has died
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
I/NotificationManager(  847): android: cancelAsUser(-1548111331) by android
,I/art     ( 4965): Explicit concurrent mark sweep GC freed 16786(1129KB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 14MB/24MB, paused 1.677ms total 122.928ms
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  847): android: cancelAsUser(898701380) by android
,I/WVCdm   (  278): CdmEngine::CloseSession
I/WVCdm   (  278): L3 Terminate.
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  847): android: cancelAsUser(-1816247584) by android
,E/Auth.Api.Credentials( 4965): [CredentialSyncAdapter] Unknown sync event.
,I/NotificationManager(  847): android: cancelAsUser(-591465577) by android
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NotificationManager(  847): android: cancelAsUser(2) by android
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 1728): propertyValue:false
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/MusicWidget( 2610): mDelayedStopHandler : unbind
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/MusicBrowser( 2666): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2666): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2666): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2666): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2666): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2666): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2666): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2666): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  847):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1149cb63com.lge.music.MediaPlaybackService$6@9f5f360
,D/MusicBrowser( 2666): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2666): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2666): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2666): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2666): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@ac42aa9
,I/MusicBrowser( 2666): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2666): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2666): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2666): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2666): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2666): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2666): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2666): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2666): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2666): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2666): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2666): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2666): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2666): reset
V/MediaPlayer[Native]( 2666): setListener
,V/MediaPlayer[Native]( 2666): disconnect
V/MediaPlayer[Native]( 2666): destructor
V/AudioFlinger(  278): releasing 19 from 2666 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/MediaPlayer[Native]( 2666): disconnect
D/MusicBrowser( 2666): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2666): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2666): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2666): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2666): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2666): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2666): [SmartShareManagerClient] unregisterListener: 169873433
W/SmartShareClient( 2666): [SmartShareManagerClient] unregisterListener invalid listener: 169873433
I/SmartShareClient( 2666): [SmartShareManagerClient] terminate service: 2666/MediaPlaybackService/722701527
E/HomeCloudIF( 2666): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2666): [SmartShareManagerClient] unbindService context:android.app.Application@20e4a8de
,V/CloudHub( 2666): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2666): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2666): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2666): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2666): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2666): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29983
,I/GCoreUlr( 1728): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1728): DispatchingService.onCreate()
,I/NotificationManager(  847): android: cancelAsUser(1222422273) by android
,I/GCoreUlr( 1728): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1728): Unbound from all location providers
I/GCoreUlr( 1728): Place inference reporting - stopped
I/GCoreUlr( 1728): DispatchingService.onDestroy()
I/GCoreUlr( 1728): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1728): Unbound from all location providers
I/GCoreUlr( 1728): Place inference reporting - stopped
I/MusicLeanback( 6610): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6610): Stop autocaching.
,E/GmsUtils( 6610): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6610): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/Adreno-EGL( 6557): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6557): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6557): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6557): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6557): Remote Branch: 
I/Adreno-EGL( 6557): Local Patches: 
I/Adreno-EGL( 6557): Reconstruct Branch: 
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  847): tsOffsetIs: Apps: 115660740951; DSPS: 3881278; Offset : -2793740772
,I/CheckinRequestBuilder( 4965): Classify the device as Phone.
,D/libc-netbsd( 4965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 4965): propertyValue:false
D/libc-netbsd( 4965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 4965): Sending checkin request (9952 bytes)
I/[SystemUI]QPairHandler( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1835): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
I/InputReader(  847): Reconfiguring input devices.  changes=0x00000010
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
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  847): Handling package changes for user 0
,I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6832 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/CheckinRequestBuilder( 4965): Checkin reason type: 8 attempt count: 1
,I/NotificationManager( 6384): com.google.android.talk: cancel(8) by com.google.android.talk
E/ActivityThread( 4965): Failed to find provider info for com.google.android.wearable.settings
W/ResourcesManager( 6384): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6384): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 6832): onCreate
,W/AppUp4:DB( 6832):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6832):  setFingerPrint start
I/AppUp4:DB( 6832):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,V/JNIHelp ( 6384): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AppUp4:DB( 6832):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6832):  SDK version = 0
I/AppUp4:DB( 6832):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6832): AppBoxApplication onCreate()
,I/jxcore-log( 5526): Test app app.js loaded
I/jxcore-log( 5526): 
,I/AppUp4:CustModeStarterReceiver( 6832): onReceive
,I/AppUp4:CustModeStarterReceiver( 6832): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6832): Context : android.app.ReceiverRestrictedContext@16d69456
D/AppUp4:CustFacade( 6832): isCustomizationCompleted : false
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f5f56ad added. We now have 1 listener(s)
,D/BluetoothAdapterService(19308080)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9dabf06
I/ActivityManager(  847): Process com.lge.clock (pid 6586) has died
D/AppUp4:CustFacade( 6832): isSimDevice : true
D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
I/jxcore-log( 5526): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5526): 
D/AppUp4:CustModeStarterReceiver( 6832): begin check event
I/AppUp4:CustModeStarterReceiver( 6832): Event For Nothing, skip.
,W/System  ( 6384): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6384): Installed default security provider GmsCore_OpenSSL
,I/NotificationService(  847): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  847): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  847): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/art     ( 4868): Explicit concurrent mark sweep GC freed 2866(116KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 395us total 42.983ms
,I/ActivityManager(  847): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6855 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/BackupManagerService(  847): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  847): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  847): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2f3469e5
,W/ResourcesManager( 6855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6855): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6855): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/ActivityManager(  847): Process com.google.android.gm (pid 6403) has died
I/chromium( 5526): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/CheckinRequestBuilder( 4965): Classify the device as Phone.
W/ResourcesManager(  847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/CheckinTask( 4965): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4965): Checking schedule, now: 1454082622783 next: 1454609871778
I/CheckinService( 4965): active receiver: disabled
,D/CheckinService( 4965): Recording last checkin time for package unspecified as 1454082622838
I/AppConfig( 6855): Total System Memory = 906309632
,I/GalleryUtils( 6855): Application Heap = 96 MB
I/AppConfig( 6855): App Tier : NOT_DEF
D/SystemHelper( 6855): region [EU], country [EU], operator [OPEN], sub-operator []
,W/ResourceType(  847): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  847): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6876 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  847): Killing 6362:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10051/pid_6362/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1728): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 6876): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6876): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6876): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LocationProviderProxy(  847): applying state to connected service
,I/ActivityManager(  847): Process com.google.android.apps.plus (pid 6099) has died
,I/SystemConfig( 6876): BUILD Country: EU
I/SystemConfig( 6876): BUILD Operator: OPEN
,I/ActivityManager(  847): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6902 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6876): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 6876): existFile = false
I/SystemConfig( 6876): canReadFile = false
I/SystemConfig( 6876): systemFeature RCS result false
D/SystemConfig( 6876): refreshRcsSupport() :false
,I/LockScreenSettings( 6902): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6902): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6902): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6902): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6902): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6902): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  847): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6919 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  847): Killing 6644:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10036/pid_6644/cgroup.procs: No such file or directory
,W/ResourcesManager( 6919): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  847): Explicit concurrent mark sweep GC freed 30672(1538KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 1.929ms total 169.955ms
,I/UpdateIcingCorporaServi( 1933): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  847): Killing 6740:com.lge.qmemoplus/1000 (adj 15): empty #11
I/UpdateIcingCorporaServi( 1933): UpdateCorporaTask done [took 75 ms] updated apps [took 74 ms] 
,I/ActivityManager(  847): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6944 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_6740/cgroup.procs: No such file or directory
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/Finsky  ( 6944): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6944): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6944): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6944): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6944): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3141): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3141): created cursor android.database.sqlite.SQLiteCursor@13d8d9cb on behalf of 6944
D/Finsky  ( 6944): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6944): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6944): Skipping gmscore version check
D/Finsky  ( 6944): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4965): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4965): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 6944): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Icing   ( 4965): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  847): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6989 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6989): Register our PhoneStateListener
,V/SetupWizard( 6989): Connected to Gservices successfully
,D/PhoneMonitor( 6989): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6989): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6989): [parse] Load xml
D/GCM     ( 1728): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
V/TelephonyAutoProfiling( 6989): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6989): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6989): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Icing   ( 4965): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4965): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  847): Killing 6610:com.google.android.music:main/u0a81 (adj 15): empty #11
I/ActivityManager(  847): Killing 2666:com.lge.music/u0a28 (adj 15): empty #12
,V/AudioFlinger(  278): 2666 died, releasing its sessions
,V/AudioFlinger(  278):  pid 1746 @ 0
V/AudioFlinger(  278):  pid 3118 @ 1
V/AudioFlinger(  278):  pid 3118 @ 2
,W/libprocessgroup(  847): failed to open /acct/uid_10081/pid_6610/cgroup.procs: No such file or directory
,W/libprocessgroup(  847): failed to open /acct/uid_10028/pid_2666/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  847): Killing 6384:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10061/pid_6384/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  485): init target 500000
,I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/charger_monitor(  485): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/WifiController(  847): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/CheckinService( 4965): Done disabling old GoogleServicesFramework version
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QPairHandler( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
,D/charger_monitor(  485): init target 500000
,I/QCNEJ   ( 1835): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  847): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/charger_monitor(  485): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7071 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 28.730ms
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,D/administrator(  847): Handling package changes for user 0
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 21.486ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.624ms
W/ResourcesManager( 7071): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  847): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  847): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  847): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  847): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,V/BackupManagerService(  847): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
V/BackupManagerService(  847): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@37f6365c
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
,W/ResourcesManager(  847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  847): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1728): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  847): applying state to connected service
,I/Babel_SMS( 7071): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7071): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7071): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7071): MmsConfig.loadFromDatabase
D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
,E/Babel_SMS( 7071): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7071): MmsConfig.loadFromResources
E/Babel_SMS( 7071): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7071): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7071): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7071): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7071): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7071): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7071): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7071): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7071): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7071): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7071): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7071): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7071): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7071): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7071): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7071): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7071): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7071): found sensor: Motion Accel, handle=46
,W/Settings( 7071): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7071): startup - clean
I/art     ( 7071): CheckpointMarkThreadRoots callback created = 0xaaf3d670
,I/Babel   ( 7071): deleted: false for 0
,I/art     ( 7071): CheckpointMarkThreadRoots callback created = 0xaaf3d650
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/AppUp4:CustModeStarterReceiver( 6832): onReceive
I/AppUp4:CustModeStarterReceiver( 6832): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6832): Context : android.app.ReceiverRestrictedContext@16d69456
,D/AppUp4:CustFacade( 6832): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6832): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6832): begin check event
I/AppUp4:CustModeStarterReceiver( 6832): Event For Nothing, skip.
W/AudioCapabilities( 7071): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7071): Unsupported mime audio/adpcm
W/AudioCapabilities( 7071): Unsupported mime audio/g726
W/AudioCapabilities( 7071): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7071): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7071): Unsupported mime video/mjpg
,W/VideoCapabilities( 7071): Unsupported mime video/theora
D/LockScreenSettings( 6902): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6902): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6902): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6902): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6902): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 1933): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 4965): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4965): Null package name or gms related package.  Ignoreing.
W/AudioCapabilities( 7071): Unsupported mime audio/evrc
,I/Icing   ( 4965): updateResources: need to parse f{com.google.android.gms}
I/UpdateIcingCorporaServi( 1933): UpdateCorporaTask done [took 45 ms] updated apps [took 45 ms] 
W/AudioCapabilities( 7071): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7071): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7071): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7071): Unsupported mime audio/qcelp
W/AudioCapabilities( 7071): Unsupported mime audio/evrc
W/VideoCapabilities( 7071): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7071): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7071): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7071): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7071): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7071): Unrecognized profile 2130706433 for video/avc
,W/art     ( 7071): Suspending all threads took: 6.804ms
,I/vclib   ( 7071): onServiceConnected
,W/Babel   ( 7071): Attempted to change video mute state without an active call.
I/NotificationManager( 7071): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7071): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7071): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7071): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7071): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7071): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7071): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/Icing   ( 4965): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4965): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{348760a1 type 2 when 130951 android} when 130951
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  847): Killing 6989:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10038/pid_6989/cgroup.procs: No such file or directory
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 135661566672; DSPS: 4536665; Offset : -2793741188
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  847): ALS enabled for SRE
,D/PowerManagerServiceEx(  847): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29285 ms ago)
D/qdlights(  847): set_light_backlight: 252
,D/qdlights(  847): set_light_backlight: 248
D/qdlights(  847): set_light_backlight: 245
,D/qdlights(  847): set_light_backlight: 242
,D/qdlights(  847): set_light_backlight: 238
,D/qdlights(  847): set_light_backlight: 235
,D/qdlights(  847): set_light_backlight: 232
,D/qdlights(  847): set_light_backlight: 228
,D/qdlights(  847): set_light_backlight: 225
,D/qdlights(  847): set_light_backlight: 222
,D/qdlights(  847): set_light_backlight: 218
,D/qdlights(  847): set_light_backlight: 215
,D/qdlights(  847): set_light_backlight: 212
,D/qdlights(  847): set_light_backlight: 208
,D/qdlights(  847): set_light_backlight: 205
,D/qdlights(  847): set_light_backlight: 202
,D/qdlights(  847): set_light_backlight: 198
,D/qdlights(  847): set_light_backlight: 195
,D/qdlights(  847): set_light_backlight: 192
,D/qdlights(  847): set_light_backlight: 188
,D/qdlights(  847): set_light_backlight: 185
,D/qdlights(  847): set_light_backlight: 182
,D/qdlights(  847): set_light_backlight: 178
,D/qdlights(  847): set_light_backlight: 175
,D/qdlights(  847): set_light_backlight: 172
,D/qdlights(  847): set_light_backlight: 168
,D/qdlights(  847): set_light_backlight: 165
,D/qdlights(  847): set_light_backlight: 162
,D/qdlights(  847): set_light_backlight: 158
,D/qdlights(  847): set_light_backlight: 155
,D/qdlights(  847): set_light_backlight: 152
,D/qdlights(  847): set_light_backlight: 148
,D/qdlights(  847): set_light_backlight: 145
,D/qdlights(  847): set_light_backlight: 142
,D/qdlights(  847): set_light_backlight: 138
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  847): set_light_backlight: 135
,D/qdlights(  847): set_light_backlight: 132
,D/qdlights(  847): set_light_backlight: 128
,D/qdlights(  847): set_light_backlight: 125
,D/qdlights(  847): set_light_backlight: 122
,D/qdlights(  847): set_light_backlight: 118
,D/qdlights(  847): set_light_backlight: 115
,D/qdlights(  847): set_light_backlight: 112
,D/qdlights(  847): set_light_backlight: 108
,D/qdlights(  847): set_light_backlight: 105
,D/qdlights(  847): set_light_backlight: 102
,D/qdlights(  847): set_light_backlight: 98
,D/qdlights(  847): set_light_backlight: 95
,D/qdlights(  847): set_light_backlight: 92
,D/qdlights(  847): set_light_backlight: 88
,D/qdlights(  847): set_light_backlight: 85
,D/qdlights(  847): set_light_backlight: 82
,D/qdlights(  847): set_light_backlight: 78
,D/qdlights(  847): set_light_backlight: 75
,D/qdlights(  847): set_light_backlight: 72
,D/qdlights(  847): set_light_backlight: 68
,D/qdlights(  847): set_light_backlight: 65
,D/qdlights(  847): set_light_backlight: 62
,D/qdlights(  847): set_light_backlight: 58
,D/qdlights(  847): set_light_backlight: 55
,D/qdlights(  847): set_light_backlight: 52
,D/qdlights(  847): set_light_backlight: 48
,D/qdlights(  847): set_light_backlight: 45
,D/qdlights(  847): set_light_backlight: 42
,D/qdlights(  847): set_light_backlight: 38
,D/qdlights(  847): set_light_backlight: 35
,D/qdlights(  847): set_light_backlight: 32
,D/qdlights(  847): set_light_backlight: 28
,D/qdlights(  847): set_light_backlight: 25
,D/qdlights(  847): set_light_backlight: 22
,D/qdlights(  847): set_light_backlight: 18
,D/qdlights(  847): set_light_backlight: 15
,D/qdlights(  847): set_light_backlight: 12
,D/qdlights(  847): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/PowerManagerServiceEx(  847): acquireWakeLockInternal: lock=559442643, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=847
,D/WeatherService( 2659): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:51:0
D/WeatherService( 2659): 2 : TimeTick Intent And Screen On
D/WeatherService( 2659): 2 : SDK version : 21
W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2659): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2659): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2659): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2659): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2659): 2 : This is isUpdating : false
D/WeatherService( 2659): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2659): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2659): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2659): 2 : Fixed theme : optimus
D/WeatherReflect( 2659): 2 : Map key string is -2
,D/lim     ( 2659): 2 : time = 16:51
I/WeatherReflect( 2659): Model Name : LG-D722
D/WeatherTheme( 2659): 2 : Different view - status_min_formatted : 50 != 51
D/WeatherTheme( 2659): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2659): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2659): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2659): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2659): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2659): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2659): forecast size is 0
,D/Theme   ( 2659): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2659): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2659): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2659): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2659): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2659): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2659): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2659): url is : null
D/Theme   ( 2659): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2659): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2659): 2 : update view, appWidgetId: 2
D/WeatherService( 2659): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:51:0
,D/PowerManagerServiceEx(  847): releaseWakeLockInternal: lock=559442643 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 155662308696; DSPS: 5192049; Offset : -2793729502
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  847): ALS enabled for SRE
D/PowerManagerServiceEx(  847): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36277 ms ago)
,I/PowerManagerService(  847): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  847): ALS enabled for SRE
D/PowerManagerServiceEx(  847): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36292 ms ago)
,W/ContextImpl(  847): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  847): Sleeping (uid 1000)...
D/LPWGController(  847): [updateScreenState] screen on = false
D/LPWGController(  847): disable proximity sensor
,D/LPWGController(  847): enable proximity sensor
I/SensorManager(  847): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3a9b62c6] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  847): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  847): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  847): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  847): activate: handle is 48, enable
V/sensors_hal_Ctx(  847): activate sensors is 1400000000000
D/sensors_hal_Thresh(  847): enable: handle=48
I/sensors_hal_SAM(  847): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  847): waitForResponse: timeout=1000
V/sensors_hal_SAM(  847): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  847): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  847): enable: Received response: 0
D/PowerManagerServiceEx(  847): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36332 ms ago)
I/Adreno-EGL(  847): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  847): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  847): Build Date: 03/02/15 Mon
I/Adreno-EGL(  847): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  847): Remote Branch: 
I/Adreno-EGL(  847): Local Patches: 
I/Adreno-EGL(  847): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (218 us)
,I/Sensors (  425): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  847): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  847): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  847): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  847): processInd: handle 48, count=1
V/sensors_hal_Thresh(  847): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  847): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  847): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  847): poll: count: 256
I/sensors_hal_Ctx(  847): poll: released wakelock sensor_ind
D/sensors_hal_Util(  847): waitForResponse: timeout=0
D/LPWGController(  847): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  847): current mode = 1  value = 1 1
I/LPWGController(  847): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  847): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  847): set_light_backlight: 0
,I/SensorManager(  847): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  847): activate: handle is 46, disable
V/sensors_hal_Ctx(  847): activate sensors is 1000000000000
D/sensors_hal_LP2(  847): enable: handle=46
D/sensors_hal_LP2(  847): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  847): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  847): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  847): Display changed displayId=0
,V/sensors_hal_SAM(  847): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  847): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
D/DSDPConnection( 1746): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  847): Excessive delay in setPowerMode(): 222ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  847): Got set_interactive hint
,D/SmartCoverViewMediator( 1328): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1369): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1328): notifyScreenOffLocked
D/SmartCoverViewMediator( 1328): handleNotifyScreenOFF
D/KeyguardViewMediator( 1369): notifyScreenOffLocked
,D/KeyguardViewMediator( 1369): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/WifiServerServiceExt(  847): sendKtScanInterval  mRtspPlay : false
D/KeyguardViewMediator( 1369): handleNotifyScreenOff
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 847
,D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: enter: screen_state=on
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  278): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
I/WifiServerServiceExt(  847): set CMD_KT_SCAN_INTERVAL
,D/ScreenTurnOffBySensor( 1369): unregisterProximitySensor
,D/StatusBarWindowView( 1369): onScreenTurnedOff why = 3
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/GpsLocationProvider(  847): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1835): |CORE| sendScreenState: state:true
,I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/LEDService( 1800): stopPatternFlashing()
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1800): lockStatus = 0
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
,D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1783): action : android.intent.action.SCREEN_ON
I/LEDService( 1800): updateLightsLocked : turn off led
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1800): RESTART MSG
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
,D/SplitWindow(  847): check instance of lgWin Window{2e1865dd u0 SearchPanel}
,I/ActivityManager(  847): Process com.google.android.gms.unstable (pid 6557) has died
,D/InputDispatcher(  847): Window went away: Window{12175989 u0 SearchPanel}
D/Ulp_jni (  847): JNI:system_update. Event-0
,I/[SystemUI]Clock( 1369): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1369): time changed, timezoneChanged : false
,V/PhoneApp( 1746): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2659): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:51:3
,D/WeatherService( 2659): 2 : ACTION screen on
D/WeatherService( 2659): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2659): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2659): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:51:3
D/AppCleanupService( 3865): android.intent.action.SCREEN_ON
,W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): ACTION_SCREEN_ON
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 847
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
D/WifiController(  847): CMD_SCREEN_OFF 
D/WifiController(  847): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  847): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1835): |CORE| sendScreenState: state:false
,I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1800): stopPatternFlashing()
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1800): clear
I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1800): updateLightsLocked : turn on led
D/LNfcService( 1783): action : android.intent.action.SCREEN_OFF
E/LEDService( 1800): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1800): Can't handle this request of patternId:0
D/LEDHandler( 1800): RESTART MSG
D/NfcServiceNXP( 1783): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1874): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1746): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2659): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:51:3
D/WeatherService( 2659): 2 : ACTION screen off
D/WeatherService( 2659): 2 : TimeTick Receiver Unregister
D/WeatherService( 2659): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:51:3
D/AppCleanupService( 3865): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3865): AppUsageStatsSaveTask
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  847): ACTION_SCREEN_OFF
E/NxpNfcJni( 1783): getReconnectState = 0x0
D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
,D/LNfcService( 1783): isRequireNfcCRouting() return true
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
,I/Sensors (  425): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{355ae552 type 2 when 160964 android} when 160964
,E/ActivityThread( 4965): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  847): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 133150, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  847): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 224792, reason: UserStart
I/NotificationManager(  847): android: cancelAsUser(716319171) by android
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/charger_monitor(  485): init target 500000
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{13644b7f type 2 when 162243 com.android.systemui} when 162243
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  847): battery changed pluggedType: 2
D/KeyguardViewMediator( 1369): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
,D/LEDHandler( 1800): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
D/PhoneUtils( 1746): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
,V/TelecomServiceImpl( 1746): getCallState : 0
,D/PhoneUtils( 1746): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1369): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1369): doKeyguard: not showing because lockscreen is off
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 175663039782; DSPS: 5847434; Offset : -2793761224
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{33ef074c type 2 when 181391 android} when 181391
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1728): disconnect managed GoogleApiClient
,D/charger_monitor(  485): init target 500000
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{21c77395 type 2 when 187654 com.google.android.gms} when 187654
,I/PhenotypeConfigurator( 1728): Scheduling Phenotype for one-off execution 140 seconds from now (1454082693852)
,D/GetConfigurationSnapshotOperation( 1728): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1728): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1728): Using platform SSLCertificateSocketFactory
,I/art     ( 1728): Explicit concurrent mark sweep GC freed 34462(2MB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 14MB/23MB, paused 1.794ms total 109.123ms
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10006
,D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  847): android: cancelAsUser(2) by android
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{2bed6c05 type 2 when 190996 android} when 190996
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 195663843836; DSPS: 6502820; Offset : -2793750915
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 215664513308; DSPS: 7158202; Offset : -2793752751
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 235665249446; DSPS: 7813586; Offset : -2793749088
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  485): init target 500000
D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 255665993657; DSPS: 8468970; Offset : -2793737402
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 275666671202; DSPS: 9124353; Offset : -2793761449
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 295667344371; DSPS: 9779735; Offset : -2793759719
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 5526): --= Surplus to requirements =--
I/jxcore-log( 5526): 
I/jxcore-log( 5526): ****TEST TOOK:  ms ****
I/jxcore-log( 5526): 
I/jxcore-log( 5526): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5526): 
,D/AndroidRuntime( 7248): 
D/AndroidRuntime( 7248): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7248): CheckJNI is OFF
,D/AndroidRuntime( 7248): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  847): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  847): Killing 5526:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  847): Skipping PackageSetting{2bed636 com.example.hello/10317} due to missing metadata
I/WindowState(  847): WIN DEATH: Window{330bb5d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  847): Focus left window: Window{330bb5d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  847): Window went away: Window{330bb5d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  847):   Force finishing activity ActivityRecord{4bf0bbf u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  847): Display changed displayId=0
,D/DSDPConnection( 1746): Display #0 changed.
W/ActivityManager(  847): Spurious death for ProcessRecord{1bdeb45a 5526:com.test.thalitest/u0a316}, curProc for 5526: null
I/ActivityManager(  847): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  847):   Force finishing activity ActivityRecord{4bf0bbf u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  847): Duplicate finish request for ActivityRecord{4bf0bbf u0 com.test.thalitest/.MainActivity t222 f}
,I/[LGHome]EVENT( 1874): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader(  847): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1835): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[LGHome]EVENT( 1874): [Launcher.java:776:onResume()]onResume
W/System.err( 3373): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3373): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3373): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3373): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3373): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3373): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3373): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3373): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3373): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3373): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/ActivityManager(  847): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7275 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     ( 4965): Explicit concurrent mark sweep GC freed 25142(1442KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/19MB, paused 939us total 150.304ms
,I/art     ( 1933): Explicit concurrent mark sweep GC freed 13577(799KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/21MB, paused 1.873ms total 163.840ms
I/[LGHome]EVENT( 1874): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1874): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1874): [Launcher.java:929:onResume()]onResume end
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
I/Activity( 1874): Activity.onPostResume() called 
D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
,W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
,W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/[LGHome]LGWallpaperInfo( 1874): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1874): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3455683,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  847): Focus entered window: Window{245f3c5d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3455683,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1369): handleShortcutListChanged...
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
,D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
I/art     (  847): Explicit concurrent mark sweep GC freed 69144(3MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 6.485ms total 279.107ms
,I/art     (  847): WaitForGcToComplete blocked for 248.540ms for cause Explicit
W/ResourcesManager( 7275): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7275): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7275): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/administrator(  847): Handling package changes for user 0
,D/KeyguardModel( 1369): handleShortcutListChanged...
,I/NotificationService(  847): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  847): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  847): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
D/TaskPersister(  847): removeObsoleteFile: deleting file=222_task.xml
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
I/LGEmail ( 7275): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7275): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/art     (  847): Explicit concurrent mark sweep GC freed 12130(799KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 10.767ms total 304.468ms
,I/art     (  847): WaitForGcToComplete blocked for 519.323ms for cause Explicit
D/AndroidRuntime( 7248): Shutting down VM
,W/ResourcesManager(  847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  847): Explicit concurrent mark sweep GC freed 4883(308KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.756ms total 191.525ms
W/GeofencerStateMachine( 1728): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
I/PhoneWindow( 1874): [setNavigationBarColor] color=0x 0
,W/InputMethodManagerService(  847): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  847): Got RemoteException sending setActive(false) notification to pid 5526 uid 10316
,W/ResourceType(  847): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/PackageChangeReceiver( 7275): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/AppUp4:PreloadHelper( 6832): added Exclude : com.test.thalitest
W/IInputConnectionWrapper( 1874): getTextBeforeCursor on inactive InputConnection
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1612): Unable to connect to the editor to retrieve text... will retry later
I/ActivityManager(  847): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7309 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/Timeline(  847): Timeline: Activity_windows_visible id: ActivityRecord{26c1a24e u0 com.lge.launcher2/.Launcher t221} time:302902
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1874): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
,W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,W/ResourcesManager( 7309): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7309): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7309): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7309): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.

```
