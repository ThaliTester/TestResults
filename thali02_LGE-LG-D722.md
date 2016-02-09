#### Test 584164489c56086_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  851): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5471 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  851): Killing 5206:com.lge.sync/1000 (adj 15): empty #11
--------- beginning of main
I/CheckinRequestBuilder( 4242): Checkin reason type: 8 attempt count: 1
W/libprocessgroup(  851): failed to open /acct/uid_1000/pid_5206/cgroup.procs: No such file or directory
,E/ActivityThread( 4242): Failed to find provider info for com.google.android.wearable.settings
I/SystemConfig( 5450): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5450): existFile = false
I/SystemConfig( 5450): canReadFile = false
I/SystemConfig( 5450): systemFeature RCS result false
D/SystemConfig( 5450): refreshRcsSupport() :false
I/LockScreenSettings( 5471): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
I/LockScreenSettings( 5471): New app installed broadcast received ..
I/LockScreenSettings( 5471): Number of installed packages  1
I/ActivityManager(  851): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5498 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/art     (  851): Explicit concurrent mark sweep GC freed 13817(756KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.464ms total 171.528ms
I/ActivityManager(  851): Killing 3926:com.google.process.gapps/u0a6 (adj 15): empty #11
E/lowmemorykiller(  240): Error opening /proc/3926/oom_score_adj; errno=2
W/libprocessgroup(  851): failed to open /acct/uid_10006/pid_3926/cgroup.procs: No such file or directory
I/ActivityThread( 4242): Removing dead content provider:android.content.ContentProviderProxy@1ed919c
I/ActivityManager(  851): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5517 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/EulaProviderUpdateObserver( 5498): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5498): uri : package:com.test.thalitest
D/[BNRAppListMgrReceiver]( 5250): android.intent.action.PACKAGE_ADDED : com.test.thalitest
D/AndroidRuntime( 5491): 
D/AndroidRuntime( 5491): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5491): CheckJNI is OFF
I/ActivityManager(  851): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5534 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  851): Killing 5140:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_10010/pid_5140/cgroup.procs: No such file or directory
I/GservicesProvider( 5517): Gservices pushing to system: true; secure/global: true
I/GoogleHttpClient( 5517): GMS http client unavailable, use old client
I/GoogleHttpClient( 5517): GMS http client unavailable, use old client
I/ActivityManager(  851): Killing 5270:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_10081/pid_5270/cgroup.procs: No such file or directory
D/AndroidRuntime( 5491): Calling main entry com.android.commands.am.Am
I/ActivityManager(  851): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  851): setTaskToReturnTo : TaskRecord{1901ea26 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  851): setTaskToReturnTo : TaskRecord{1901ea26 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  851): AppWindowTokenEx init.. 
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/ContextHelper(  851): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  851): Focus left window: Window{156f934b u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5491): Shutting down VM
I/PhoneWindow(  851): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx(  851): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  851): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  851): check instance of lgWin Window{e2217fe u0 Starting com.test.thalitest}
I/ActivityManager(  851): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5577 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
V/AlarmManager(  851): ELAPSED_WAKEUP set : Alarm{3447cb5f type 2 when 80409 android} when 80409
I/HotwordDetector( 1936): Closing mic
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  851): Starting window displayed
I/MicrophoneInputStream( 1936): mic_close com.google.android.apps.gsa.speech.audio.u@261ca468
D/WindowManager(  851): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  851): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
I/[SystemUI]NavigationThemeResource( 1372): notify navigation bar color(0xfff5f5f5)
W/PhoneWindowManagerEx(  851): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  851): setLGSystemUiVisibility(0x0)
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
D/StatusBarManagerServiceEx(  851): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  851): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@12a8d99c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  851): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioRecord( 1936): stop()
D/AudioRecord( 1936): AudioRecord->stop()
V/AudioFlinger(  277): RecordHandle::stop()
V/AudioFlinger(  277): RecordThread::stop
V/AudioFlinger(  277): Record stopped OK
V/AudioPolicyManager(  277): stopInput() input 17
V/AudioPolicyService(  277): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  277): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  277): AudioCommandThread() waking up
V/AudioPolicyService(  277): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  277): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  277): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  277): ThreadBase::setParameters() routing=0
V/AudioFlinger(  277): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  277): processConfigEvents_l() remaining events 1
V/AudioFlinger(  277): processConfigEvents_l() DONE thread 0xb3a63000
D/audio_hw_primary(  277): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
,W/System.err( 4890): java.net.SocketTimeoutException
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/System.err( 4890): 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:598)
W/System.err( 4890): 	at libcore.io.IoBridge.recvfrom(IoBridge.java:556)
W/System.err( 4890): 	at java.net.PlainDatagramSocketImpl.doRecv(PlainDatagramSocketImpl.java:163)
W/System.err( 4890): 	at java.net.PlainDatagramSocketImpl.receive(PlainDatagramSocketImpl.java:171)
W/System.err( 4890): 	at java.net.DatagramSocket.receive(DatagramSocket.java:274)
W/System.err( 4890): 	at com.lge.drmservice.activation.DrmSntpClient.processRequest(DrmSntpClient.java:257)
W/System.err( 4890): 	at com.lge.drmservice.activation.DrmSntpClient.run(DrmSntpClient.java:127)
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/System.err( 4890): Caused by: android.system.ErrnoException: recvfrom failed: EAGAIN (Try again)
W/System.err( 4890): 	at libcore.io.Posix.recvfromBytes(Native Method)
W/System.err( 4890): 	at libcore.io.Posix.recvfrom(Posix.java:161)
W/System.err( 4890): 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
W/System.err( 4890): 	at libcore.io.IoBridge.recvfrom(IoBridge.java:553)
W/System.err( 4890): 	... 5 more
D/DrmSntpClient( 4890): Server : 1
D/libc-netbsd( 4890): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4890): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4890): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4890): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  273): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
V/audio_hw_primary(  277): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  277): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  277): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  277): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  277): disable_audio_route: exit
E/audio_hw_primary(  277): disable_snd_device: enter 144
D/hardware_info(  277): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  277): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  277): stop_input_stream: exit: status(0)
V/audio_hw_primary(  277): in_standby: exit:  status(0)
V/AudioFlinger(  277): RecordThread: loop stopping
V/AudioPolicyService(  277): AudioCommandThread() going to sleep
V/AudioPolicyManager(  277): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  277): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  277): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  277): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  277): AudioCommandThread() waking up
V/AudioPolicyService(  277): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  277): AudioCommandThread() going to sleep
V/AudioPolicyService(  277): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  277): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  277): AudioCommandThread() waking up
V/AudioPolicyService(  277): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  277): setParameters(): io 17, keyvalue hotword_active=0, calling pid 277
V/AudioFlinger(  277): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  277): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  277): RecordThread: loop starting
V/AudioFlinger(  277): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  277): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  277): in_set_parameters: exit: status(0)
V/AudioFlinger(  277): processConfigEvents_l() DONE thread 0xb3a63000
V/AudioFlinger(  277): RecordThread: loop stopping
V/AudioPolicyService(  277): AudioCommandThread() going to sleep
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioFlinger(  277): RecordHandle::stop()
V/AudioFlinger(  277): RecordThread::stop
V/AudioPolicyManager(  277): releaseInput() 17
V/AudioPolicyManager(  277): closeInput(17)
V/AudioFlinger(  277): releasing 16 from 1936 for -1
V/AudioFlinger(  277):  decremented refcount to 0
V/AudioFlinger(  277): purging stale effects
V/AudioFlinger(  277): closeInput() 17
V/AudioSystem(  277): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  851): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  277): ThreadBase::exit
V/AudioSystem( 1748): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  277): RecordThread: loop starting
V/AudioSystem( 1936): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  277): RecordThread 0xb3a63000 exiting
D/audio_hw_primary(  277): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  277): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  277): in_standby: exit:  status(0)
V/AudioPolicyService(  277): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  277): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  277): releaseInput() exit
V/AudioPolicyService(  277): AudioCommandThread() waking up
V/AudioFlinger(  277): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  277): AudioCommandThread() processing update audio port list
V/AudioFlinger(  277): removeClient_l() pid 1936, calling pid 277
V/AudioPolicyService(  277): AudioCommandThread() going to sleep
V/AudioSystem( 3162): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1986): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2792): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1936): Stopping hotword detection.
I/HotwordRecognitionRnr( 1936): Hotword detection finished
I/CheckinRequestBuilder( 4242): Classify the device as Phone.
D/ContextHelper( 5577): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/CheckinTask( 4242): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 4242): Checking schedule, now: 1455009591113 next: 1455536840109
I/CheckinService( 4242): active receiver: disabled
D/CheckinService( 4242): Recording last checkin time for package unspecified as 1455009591149
I/ActivityManager(  851): Killing 5352:com.lge.email/u0a21 (adj 15): empty #11
I/WebViewFactory( 5577): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  851): Killing 5330:com.android.providers.calendar/u0a14 (adj 15): empty #12
D/AlertService( 3771): Beginning updateAlertNotification
W/libprocessgroup(  851): failed to open /acct/uid_10021/pid_5352/cgroup.procs: No such file or directory
W/libprocessgroup(  851): failed to open /acct/uid_10014/pid_5330/cgroup.procs: No such file or directory
I/ActivityManager(  851): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5605 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/LibraryLoader( 5577): Time to load native libraries: 1 ms (timestamps 861-862)
I/LibraryLoader( 5577): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5577): Binding Chromium to main looper Looper (main, tid 1) {a8b3282}
I/LibraryLoader( 5577): Expected native library version number "",actual native library version number ""
I/chromium( 5577): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5577): Initializing chromium process, singleProcess=true
W/art     ( 5577): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5577): ApplicationContext is null in ApplicationStatus
W/ResourcesManager( 5605): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/chromium( 5577): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5577): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5577): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5577): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5577): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5577): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5577): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5577): Remote Branch: 
I/Adreno-EGL( 5577): Local Patches: 
I/Adreno-EGL( 5577): Reconstruct Branch: 
D/CalendarProvider2( 5605): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2cc873b8
D/CalendarProvider2( 5605): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5605): Created com.android.providers.calendar.CalendarAlarmManager@8b1e9cd(com.android.providers.calendar.CalendarProvider2@2cc873b8)
D/AlertService( 3771): No fired or scheduled alerts
I/NotificationManager( 3771): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(18) by com.android.calendar
I/GAv4    ( 5534): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5534):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5534):   adb logcat -s GAv4
I/NotificationManager( 3771): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3771): com.android.calendar: cancel(20) by com.android.calendar
V/AudioPolicyService(  277): registerClient() client 0xb551c8a0, uid 10316
D/AlertService( 3771): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  851): Killing 5376:com.google.android.partnersetup/u0a9 (adj 15): empty #11
D/BluetoothManagerService(  851): Message: 20
D/BluetoothManagerService(  851): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b8f3d9d:true
D/BluetoothAdapterService(1040209353)( 1986): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37842de7
W/libprocessgroup(  851): failed to open /acct/uid_10009/pid_5376/cgroup.procs: No such file or directory
W/GAv4    ( 5534): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/AlarmScheduler( 3771): No events found starting within 1 week.
W/GAv4    ( 5534): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5534): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5534): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,W/art     ( 5577): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5577): onDetachedFromWindow called when already detached. Ignoring
,W/art     ( 5534): Suspending all threads took: 5.390ms
I/PhoneWindow( 5577): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 5577): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 5577): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 5577): CordovaWebView is running on device made by: LGE
,W/art     ( 5577): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5577): Attempt to remove local handle scope entry from IRT, ignoring
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5534): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
I/Activity( 5577): Activity.onPostResume() called 
D/OpenGLRenderer( 5577): Render dirty regions requested: true
,I/OpenGLRenderer( 5577): Initialized EGL, version 1.4
W/ResourcesManager( 5534): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/OpenGLRenderer( 5577): Enabling debug mode 0
D/Atlas   ( 5577): Validating map...
,I/ActivityManager(  851): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5660 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/SplitWindow(  851): check instance of lgWin Window{1f11c2f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/chromium( 5577): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/ActivityManager(  851): Killing 4979:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,I/art     ( 5534): CheckpointMarkThreadRoots callback created = 0xaaf01f70
V/JNIHelp ( 5534): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 5534): CheckpointMarkThreadRoots callback created = 0xb050fa60
,W/System  ( 5534): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5534): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  851): failed to open /acct/uid_10006/pid_4979/cgroup.procs: No such file or directory
W/ActivityManager(  851): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5660): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/InputDispatcher(  851): Focus entered window: Window{1f11c2f u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputMethodManagerService(  851): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  851): Displayed com.test.thalitest/.MainActivity: +1s329ms
I/Timeline(  851): Timeline: Activity_windows_visible id: ActivityRecord{3a8c7667 u0 com.test.thalitest/.MainActivity t222} time:81648
I/Timeline( 5577): Timeline: Activity_idle id: android.os.BinderProxy@1c578b2c time:81666
,W/BindingManager( 5577): Cannot call determinedVisibility() - never saw a connection for the pid: 5577
,D/JsMessageQueue( 5577): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  851): Killing 5395:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10011/pid_5395/cgroup.procs: No such file or directory
,I/ActivityManager(  851): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5696 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  851): Process com.google.android.gms (pid 4242) has died
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 109 ms] updated apps [took 109 ms] 
,D/jxcore_app_log( 5577): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426488704
,I/chromium( 5577): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 5577): CheckpointMarkThreadRoots callback created = 0x9b1a84a0
,I/art     ( 5577): CheckpointMarkThreadRoots callback created = 0x9b1a8470
,D/Finsky  ( 5696): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5696): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5696): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5696): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5696): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  851): Process com.android.contacts (pid 5450) has died
,V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@d25033a on behalf of 5696
I/NotificationManager( 5696): com.android.vending: cancel(1003285959) by com.android.vending
D/Ads     ( 5696): Skipping gmscore version check
,D/Finsky  ( 5696): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5696): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  851): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5748 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 24.471ms
,D/Finsky  ( 5696): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 22.630ms
,D/Finsky  ( 5696): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 5696): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 332us total 23.226ms
,W/ResourcesManager( 5748): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5748): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5748): VM with version 2.1.0 has multidex support
I/MultiDex( 5748): install
I/MultiDex( 5748): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  851): Process com.android.gallery3d (pid 5431) has died
,I/art     (  851): Explicit concurrent mark sweep GC freed 19829(997KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.359ms total 154.533ms
,V/JNIHelp ( 5748): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5748): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5748): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24a8bf45: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5748): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5748): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5748): com.google.android.gms: cancel(39789) by com.google.android.gms
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
D/PackageBroadcastService( 5748): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 5748): Reading stored module config
D/ChimeraCfgMgr( 5748): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5748): Loading module APK com.google.android.play.games
,I/ActivityManager(  851): Process com.lge.lockscreensettings (pid 5471) has died
,D/NativeLibraryUtils( 5748): Install completed successfully. count=14 extracted=0
,W/art     ( 5577): Suspending all threads took: 21.806ms
,W/jxcore-log( 5577): Initializing JXcore engine
W/jxcore-log( 5577): JXcore engine is ready
I/art     ( 5577): Background sticky concurrent mark sweep GC freed 12204(1142KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 22.930ms total 51.824ms
I/art     ( 5748): CheckpointMarkThreadRoots callback created = 0xb042d400
,W/Thread-661( 5715): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7476]" dev="sockfs" ino=7476 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-661( 5715): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-661( 5715): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6509]" dev="sockfs" ino=6509 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-661( 5715): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,W/Thread-661( 5715): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-661( 5715): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26237]" dev="sockfs" ino=26237 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5577): Starting JXcore engine
,I/art     ( 5748): CheckpointMarkThreadRoots callback created = 0xb042d3e0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/ChimeraCfgMgr( 5748): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5748): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 5748): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5748): Submit a task: k
,D/ChimeraCfgMgr( 5748): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5748): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/PeopleDatabaseHelper( 5748): cleanUpNonGplusAccounts done.
D/k       ( 5748): Processing package: com.test.thalitest
D/GassUtils( 5748): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5748): Found info for package com.test.thalitest in db.
,W/jxcore-log( 5577): Platform android
W/jxcore-log( 5577): 
W/jxcore-log( 5577): Process ARCH arm
W/jxcore-log( 5577): 
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5748): Restart initialization of location
,I/Icing   ( 5748): Storage manager: low false usage 1.75MB avail 2.38GB capacity 4.06GB
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
W/BaseAppContext( 5748): Using Auth Proxy for data requests.
,I/art     ( 5748): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5748): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  851): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5797 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/BaseAppContext( 5748): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5748): Using Auth Proxy for data requests.
,W/BaseAppContext( 5748): Using Auth Proxy for data requests.
,W/BaseAppContext( 5748): Using Auth Proxy for data requests.
,W/BaseAppContext( 5748): Using Auth Proxy for data requests.
W/BaseAppContext( 5748): Using Auth Proxy for data requests.
W/IcingInternalCorpora( 5748): getNumBytesRead when not calculated.
W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 1730): location=null
W/BaseAppContext( 5748): Using Auth Proxy for data requests.
,W/ActivityManager(  851): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/art     ( 5517): Explicit concurrent mark sweep GC freed 7940(400KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 913us total 49.675ms
,E/lowmemorykiller(  240): Error writing /proc/5498/oom_score_adj; errno=22
,I/jxcore-log( 5577): JXcore Cordova bridge is ready!
I/jxcore-log( 5577): 
,W/jxcore-log( 5577): JXcore engine is started
I/ActivityManager(  851): Process com.lge.eula (pid 5498) has died
,D/ChimeraCfgMgr( 5748): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5748): Module APK com.google.android.play.games already loaded
I/BackgroundMemoryTrimmer( 1936): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1748): onTrimMemory: 10
I/PhoneApp( 1748): trim memory
,D/InitAlarmsService( 3771): Clearing and rescheduling alarms.
D/CalendarProvider2( 5605): Scheduling check of next Alarm
,D/CalendarProvider2( 5605): SCHEDULE_ALARM_REMOVE
I/Gmail   ( 5797): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 5748): Background sticky concurrent mark sweep GC freed 16015(1501KB) AllocSpace objects, 14(224KB) LOS objects, 12% free, 12MB/14MB, paused 21.009ms total 107.796ms
W/GAV2    ( 5797): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Icing   ( 5748): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  851): Process com.lge.bnr (pid 5250) has died
,I/ActivityManager(  851): Waited long enough for: ServiceRecord{213f4349 u0 com.lge.drmservice/.DrmService}
W/ActivityManager(  851): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  851): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/jxcore-log( 5577): Toggling radios to true
I/jxcore-log( 5577): 
D/BluetoothAdapter( 5577): enable(): BT is already enabled..!
W/ActivityManager(  851): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/AlarmManager(  851): RTC_WAKEUP set : Alarm{3d39cafc type 0 when 1455009595985 com.google.android.googlequicksearchbox} when 1455009595985
,D/WifiServiceImplEx(  851): setWifiEnabled: true pid=5577, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
I/Gmail   ( 5797): Observing account changes for notifications
D/WifiService(  851): setWifiEnabled: true pid=5577, uid=10316
D/WifiServiceImplEx(  851): disconnect pid=5577, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  851): reconnect pid=5577, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5577): Radios toggled
I/jxcore-log( 5577): 
I/jxcore-log( 5577): My device name is: LGE-LG-D722
I/jxcore-log( 5577): 
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2762): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/Gmail   ( 5797): Error finding the version of the Email provider.....
E/Gmail   ( 5797): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5797): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5797): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5797): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5797): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5797): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5797): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5797): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5797): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2762): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  851): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  851): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1801): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,D/LGWifiP2pService(  851): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  851): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  851): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  273): Clearing all IP addresses on wlan0
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 7
,D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
,W/System.err( 4890): java.net.UnknownHostException: Unable to resolve host "nist1-la.ustiming.org": No address associated with hostname
W/System.err( 4890): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:482)
W/System.err( 4890): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:255)
W/System.err( 4890): 	at java.net.InetAddress.getByName(InetAddress.java:308)
W/System.err( 4890): 	at com.lge.drmservice.activation.DrmSntpClient.processRequest(DrmSntpClient.java:231)
W/System.err( 4890): 	at com.lge.drmservice.activation.DrmSntpClient.run(DrmSntpClient.java:127)
W/System.err( 4890): Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
W/System.err( 4890): 	at libcore.io.Posix.android_getaddrinfo(Native Method)
W/System.err( 4890): 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
W/System.err( 4890): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:446)
W/System.err( 4890): 	... 4 more
D/DrmSntpClient( 4890): Server : 2
D/DSQN    (  851): DNS error code is not timeout ignore
V/NativeCrypto( 1730): Read error: ssl=0xb045ac00: I/O error during system call, Connection timed out
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1730): SSL shutdown failed: ssl=0xb045ac00: I/O error during system call, Broken pipe
D/libc-netbsd( 4890): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4890): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4890): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4890): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  273): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=100
,D/DSQN    (  851): DNS error code is not timeout ignore
W/System.err( 4890): java.net.UnknownHostException: Unable to resolve host "time-nw.nist.gov": No address associated with hostname
W/System.err( 4890): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:482)
W/System.err( 4890): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:255)
W/System.err( 4890): 	at java.net.InetAddress.getByName(InetAddress.java:308)
W/System.err( 4890): 	at com.lge.drmservice.activation.DrmSntpClient.processRequest(DrmSntpClient.java:231)
W/System.err( 4890): 	at com.lge.drmservice.activation.DrmSntpClient.run(DrmSntpClient.java:127)
W/System.err( 4890): Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
W/System.err( 4890): 	at libcore.io.Posix.android_getaddrinfo(Native Method)
W/System.err( 4890): 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
W/System.err( 4890): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:446)
W/System.err( 4890): 	... 4 more
D/DrmSntpClient( 4890): Server : 3
D/WifiHS20(  851): hidePasspointNotification off =false
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:56.154 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  851): hidePasspointNotification off =false
D/ConnectivityService(  851): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  851): ignoring duplicate network state non-change
E/WifiStateMachine(  851): Start Disconnecting Watchdog 1
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:56.164 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/wpa_supplicant( 2762): wlan0: CTRL-EVENT-SCAN-STARTED 
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  851): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/LGWifiP2pService(  851): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  851): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc-netbsd( 4890): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4890): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4890): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4890): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/ConnectivityService(  851): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): ValidatedState{ when=-5ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): DefaultState{ when=-22ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): Forcing reevaluation
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/CommandListener(  273): Clearing all IP addresses on wlan0
,E/BandwidthController(  273): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  273): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/ConnectivityService(  851): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  851): disableDataServiceNotify
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  851): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiHS20(  851): hidePasspointNotification off =false
W/System.err( 4890): java.net.UnknownHostException: Unable to resolve host "nist1-ny.ustiming.org": No address associated with hostname
W/System.err( 4890): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:482)
W/System.err( 4890): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:255)
W/System.err( 4890): 	at java.net.InetAddress.getByName(InetAddress.java:308)
W/System.err( 4890): 	at com.lge.drmservice.activation.DrmSntpClient.processRequest(DrmSntpClient.java:231)
W/System.err( 4890): 	at com.lge.drmservice.activation.DrmSntpClient.run(DrmSntpClient.java:127)
W/System.err( 4890): Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
W/System.err( 4890): 	at libcore.io.Posix.android_getaddrinfo(Native Method)
W/System.err( 4890): 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
W/System.err( 4890): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:446)
W/System.err( 4890): 	... 4 more
D/DrmSntpClient( 4890): Server : 4
D/DSQN    (  851): stop dsqn bin
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:56.286 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/DrmSntpClient( 4890): Automatic sync but WiFi isn't enabled
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/WifiNetworkAgent(  851): NetworkAgent: NetworkAgent channel lost
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:56.304 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiHS20(  851): hidePasspointNotification off =false
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService(  851): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
W/GCoreFlp( 1730): No location to return for getLastLocation()
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
W/FusedLocationProvider( 1730): location=null
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:56.316 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  851):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService(  851):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DhcpStateMachine(  851): StoppedState
D/DhcpStateMachine(  851): StoppedState{ when=-149ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/WifiServerServiceExt(  851): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  851): setSupplicantStateDISCONNECTED
D/DrmService( 4890): Completed !! request = 2
D/DrmService( 4890): Request count = 0
,D/WifiServerServiceExt(  851): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  851): setSupplicantStateSCANNING
D/ConnectivityService(  851): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  851): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): Disconnected - quitting
V/DrmService( 4890): Service onDestroy
D/CSLegacyTypeTracker(  851): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  851): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  851): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  851): MasterInitialState.processMessage what=3
V/NetworkPolicy(  851): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1836): |CORE| No family connected
D/ConnectivityService(  851): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  851): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  851): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  851): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/Tethering(  851): MasterInitialState.processMessage what=3
D/ConnectivityService(  851): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  851): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  851): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  851):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1748): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = -1
D/NetworkManagementService(  851): Removing idletimer
W/Settings(  851): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/InstanceID/Rpc( 5748): Found 10006
,I/ActivityManager(  851): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5872 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/art     ( 5748): Background sticky concurrent mark sweep GC freed 10843(806KB) AllocSpace objects, 8(128KB) LOS objects, 7% free, 13MB/14MB, paused 8.980ms total 48.170ms
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Gmail   ( 5797): notifyAccountChanged
,I/Gmail   ( 5797): getAccountsCursor
I/Gmail   ( 5797): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5797): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Icing   ( 5748): Internal init done: storage state 0
,D/PhoneMonitor( 5872): Register our PhoneStateListener
I/NotificationManager( 5748): com.google.android.gms: cancel(10436) by com.google.android.gms
I/Icing   ( 5748): Post-init done
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5797): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5797): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PhoneMonitor( 5872): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5872): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5872): [parse] Load xml
V/TelephonyAutoProfiling( 5872): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5872): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CalendarProvider2( 5605): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5605): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/PhoneMonitor( 5872): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/art     (  851): Explicit concurrent mark sweep GC freed 33360(1538KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 1.959ms total 147.159ms
,I/ActivityManager(  851): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5899 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/Gmail   ( 5797): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2762): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,W/ResourcesManager( 5899): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LocSvc_java(  851): onReceive
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:57.335 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:57.338 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2762): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiServerServiceExt(  851): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  851): setSupplicantStateASSOCIATED
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  851): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  851): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:57.384 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:57.387 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2762): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2762): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/WifiServiceExtension(  851): setVHTCapabilityType  : false
,I/WifiServerServiceExt(  851): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  851): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,I/WifiServiceExtension(  851): setSecurityType  : 2
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:57.446 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:57.447 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/ConnectivityService(  851): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transpo,rts: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  851): Got NetworkAgent Messenger
D/ConnectivityService(  851): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  851): NetworkAgent connected
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
E/WifiConfigStore(  851): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  851): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  273): Setting iface cfg
E/WifiStateMachine(  851): Start Dhcp Watchdog 2
D/DhcpStateMachine(  851): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  851): WaitBeforeStartState
D/WifiServerServiceExt(  851): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  851): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  851): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/Babel_SMS( 5899): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5899): MmsConfig.loadMmsSettings
I/Babel_SMS( 5899): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5899): MmsConfig.loadFromDatabase
E/WifiStateMachine(  851): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  851): Current State is mWaitBeforeStartState.
,D/LGWifiP2pService(  851): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c969bfc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  851): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c969bfc target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  851): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  851): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  851): DHCP Start wake lock is acquired.
D/CommandListener(  273): Setting iface cfg
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  273): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  851): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  851): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  851): setSupplicantStateCOMPLETED
D/ConnectivityService(  851): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  851): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  851): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  851): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  851): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  851): ignoring duplicate network state non-change
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  851): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  851): Adding iface wlan0 to network 101
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:57.604 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:57.611 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  851): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:57.615 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
E/WifiStateMachine(  851): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService(  851): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  851): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  851): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  273): netlink response contains error (File exists)
,D/ConnectivityService(  851): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:57.63 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/WifiHS20(  851): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService(  851): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  851): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  851): Setting Dns servers for network 101 to [/192.168.1.1]
,D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/Nat464Xlat(  851): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  851): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  851): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  851): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  851):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  851):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  851):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  851):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  851):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  851): currentScore = 0, newScore = 20
,D/ConnectivityService(  851):    accepting network in place of null
D/ConnectivityService(  851): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  851): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  851): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  851): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI    (  851): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  851):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1748): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/Tethering(  851): MasterInitialState.processMessage what=3
,W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  851): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  851): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  851): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  851): validation of new default Network = false
D/ConnectivityService(  851): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  851): enableDataServiceNotify 
D/DSQN    (  851): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): [LWD] wait 500ms before dns check
E/Babel_SMS( 5899): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5899): MmsConfig.loadFromResources
E/Babel_SMS( 5899): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5899): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/ConnectivityService(  851): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  851):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  851):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  851): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
V/NetworkPolicy(  851): [LG_RESTRICTED] checkMobilePolicy_type()
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/DSQN    ( 5938): DSQN samuel.seo ver 141203
E/DSQN    ( 5938): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5938): created command queue thread
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/DSQN    ( 5938): Interface wlan0 address 192.168.1.134 0xc0a80186
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/DSQN    ( 5938): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/CheckinService( 5748): Checkin interval check for package: unspecified last checkin: 1455009591149 min interval config: 0 actual interval: 6589
,D/SensorManager( 5899): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5899): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5899): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5899): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5899): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5899): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5899): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5899): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5899): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5899): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5899): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5899): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5899): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5899): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5899): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5899): found sensor: Motion Accel, handle=46
I/CheckinService( 5748): Disabling old GoogleServicesFramework version
,D/DhcpStateMachine(  851): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  851): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  851): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/dhcpcd  ( 5944): version 5.5.6 starting
E/dhcpcd  ( 5944): get_duid: Read-only file system
W/Settings( 5899): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5899): startup - clean
I/Babel   ( 5899): deleted: false for 0
,I/Icing   ( 5748): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/dhcpcd  ( 5944): wlan0: rebinding lease of 192.168.1.134
,I/art     ( 5899): CheckpointMarkThreadRoots callback created = 0xaaf3d810
,I/CheckinService( 5748): Checking schedule, now: 1455009597942 next: 1455009621109
I/CheckinService( 5748): active receiver: disabled
,I/dhcpcd  ( 5944): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/art     ( 5899): CheckpointMarkThreadRoots callback created = 0xaaf3d7f0
D/Icing   ( 5748): Loaded CLD2 Version V2.0 - 20141016
,I/dhcpcd  ( 5944): wlan0: leased 192.168.1.134 for 86400 seconds
,W/art     ( 5899): Suspending all threads took: 5.158ms
I/Icing   ( 5748): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): [LWD] DNSResolver start dns
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  851): Process com.android.calendar (pid 3771) has died
,V/AlarmManager(  851): ELAPSED_WAKEUP set : Alarm{11a1f266 type 2 when 87676 com.google.android.gms} when 87676
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
W/AudioCapabilities( 5899): Unsupported mime audio/x-lg-flac
,I/System.out(  851): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/AudioCapabilities( 5899): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5899): Unsupported mime audio/g726
W/AudioCapabilities( 5899): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5899): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5899): Unsupported mime video/mjpg
W/VideoCapabilities( 5899): Unsupported mime video/theora
,I/DSQN    ( 5938): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5938): restart monitoring
I/DSQN    ( 5938): dsqn report finish
D/LGDataListener(  273): argv[0]=dsqncommand
D/LGDataListener(  273): argv[1]=wlan0
D/LGDataListener(  273): argv[2]=1
D/LGDataListener(  273): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  851): DSQM DsqnNotification wlan0  1
D/DSQN    (  851): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 09:19:58 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455009598241], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455009598226]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  851): Validated
D/ConnectivityService(  851): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  851): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  851):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  851):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  851): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  851):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  851): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  851): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  851):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  851):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  851): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  851): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  851): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1748): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
,I/WifiServerServiceExt(  851): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  851): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  851):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/AudioCapabilities( 5899): Unsupported mime audio/evrc
,W/AudioCapabilities( 5899): Unsupported mime audio/qcelp
W/VideoCapabilities( 5899): Unrecognized profile 2130706433 for video/avc
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/AudioCapabilities( 5899): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5899): Unsupported mime audio/qcelp
W/AudioCapabilities( 5899): Unsupported mime audio/evrc
W/VideoCapabilities( 5899): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5899): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5899): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5899): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5899): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5899): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5899): onServiceConnected
,W/Babel   ( 5899): Attempted to change video mute state without an active call.
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  851): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  851): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  851): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  851): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  851): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  851): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  851): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  851): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  851): RunningState
I/NotificationManager( 5899): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 5899): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5899): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  851): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5981 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/AudioManager( 5230): getMode name:com.lge.qremote
D/ConnectivityService(  851): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  851): identical MTU - not setting
,D/Nat464Xlat(  851): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  851): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  851):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  851):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  851): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  851): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  851): enableDataServiceNotify 
D/DSQN    (  851): start dsqn bin
D/DSQN    (  851): dsqn is running restart
,I/DSQN    ( 5987): DSQN samuel.seo ver 141203
E/DSQN    ( 5987): DSQN sock connect success to lgdatalistenerd
,I/DSQN    ( 5987): created command queue thread
I/DSQN    ( 5987): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5987): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524295
V/JNIHelp ( 5899): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  851): Process com.google.android.apps.docs (pid 5534) has died
I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:19:58.595 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/AudioManager( 5230): getMode name:com.lge.qremote
,W/art     ( 5899): Suspending all threads took: 5.284ms
I/AudioManager( 5230): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5981): Quickset Services start...
,I/UEI.SmartControl( 5981): Manufacture = LGE
D/UEI.SmartControl( 5981): File observer start...
E/UEI.SmartControl( 5981): IR Port is disabled: false
D/UEI.SmartControl( 5981): Starting file observer...
D/UEI.SmartControl( 5981): Extracting JNI libs...
D/UEI.SmartControl( 5981): --- this system supports 32-bit or 64-bit only
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/AudioManager( 5230): getMode name:com.lge.qremote
I/AudioManager( 5230): getMode name:com.lge.qremote
D/ConnectivityService(  851): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/MDM     ( 1730): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5748): Restart initialization of location
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/System  ( 5899): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProviderInstaller( 5899): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,D/UEI.SmartControl( 5981): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5981): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5981): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/NotificationManager( 5899): com.google.android.talk: cancel(8) by com.google.android.talk
I/UEI.SmartControl( 5981): --- Selecting new region: 2
,I/UEI.SmartControl( 5981): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5981): Platform has CIR...
D/UEI.SmartControl( 5981): NO CIR support, need to check package...
I/UEI.SmartControl( 5981): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5981): QS Service created
I/ActivityManager(  851): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6011 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,E/UEI.SmartControl( 5981): QS start get config
,D/UEI.SmartControl( 5981): Loading JNI Libs...
,D/UEI.SmartControl( 5981):  configuring local db...
I/AppUp4:AppBoxCP( 6011): onCreate
W/AppUp4:DB( 6011):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6011):  setFingerPrint start
I/AppUp4:DB( 6011):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6011):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6011):  SDK version = 0
I/AppUp4:DB( 6011):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6011): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6011): onReceive
I/AppUp4:CustModeStarterReceiver( 6011): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6011): Context : android.app.ReceiverRestrictedContext@69118f7
D/AppUp4:CustFacade( 6011): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6011): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6011): begin check event
I/AppUp4:CustModeStarterReceiver( 6011): Event For Nothing, skip.
I/ActivityManager(  851): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6030 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 5981):  ---- Has DB8: true
,W/ResourcesManager( 6030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6030): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6030): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5981): QS start statue = true Error code = 0
,D/UEI.SmartControl( 5981): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5981): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5981): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5981): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5981): IrrcClient ++ 
D/irrcClient( 5981): getIrrcService ++ 
,D/irrcClient( 5981): getIrrcService -- 
D/irrcClient( 5981): IrrcClient -- 
W/irrc_jni( 5981): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5981): Services init done
D/UEI.SmartControl( 5981): QS Service init finished
,D/UEI.SmartControl( 5981): QS Service version name: 0.1.73
,D/UEI.SmartControl( 5981): QS Service version code: 1073
D/UEI.SmartControl( 5981): Service requested: Control
I/UEI.SmartControl( 5981): Device manager: loading config....
D/ConnectivityService(  851): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  851): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  851): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  851): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  851): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  851): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/UEI.SmartControl( 5981): Config is loaded...
D/LocSvc_java(  851): onReceive
D/LocSvc_java(  851): got connectivity action
,D/LocSvc_java(  851): broadcast - no network connections
D/LocSvc_java(  851): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  851): Sending msg: 4 arg1:0 arg2:1
D/UEI.SmartControl( 5981): Request IControl service: devices are loaded...
D/LocSvc_java(  851): onReceive
D/LocSvc_java(  851): got connectivity action
D/LocSvc_java(  851): broadcast - no network connections
D/LocSvc_java(  851): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  851): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  851): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  851): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  851): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  851): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  851): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  851): ignore wifi update if we are not in OPENING or CLOSING
D/UEI.SmartControl( 5981):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5981): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5981): Internal service binding...
,I/ActivityManager(  851): Process com.android.vending (pid 5696) has died
,D/UEI.SmartControl( 5981): -----IControl: 11
D/UEI.SmartControl( 5981): Caller: com.lge.qremote
D/UEI.SmartControl( 5981): ------------ IControl registerCallback...
,I/UEI.SmartControl( 5981): Registering callback...
D/UEI.SmartControl( 5981): -----IControl: 19
D/UEI.SmartControl( 5981): Caller: com.lge.qremote
I/UEI.SmartControl( 5981): Registering Services Ready callback...
I/UEI.SmartControl( 5981): Notify client services are ready...
D/UEI.SmartControl( 5981): -----IControl: 8
D/UEI.SmartControl( 5981): Caller: com.lge.qremote
I/AppConfig( 6030): Total System Memory = 906309632
,I/GalleryUtils( 6030): Application Heap = 96 MB
I/AppConfig( 6030): App Tier : NOT_DEF
,D/SystemHelper( 6030): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  851): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6052 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ResourcesManager( 6052): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6052): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6052): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6052): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6052): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6052): BUILD Country: EU
I/SystemConfig( 6052): BUILD Operator: OPEN
,I/ActivityManager(  851): Process com.google.android.gm (pid 5797) has died
,I/ActivityManager(  851): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6074 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6052): pm.hasSystemFeature(com.lge.ims.rcs) = false
D/WeatherService( 2777): 2 : TimeTick Intent has been received, Time(hour:min:sec) 10:20:0
D/WeatherService( 2777): 2 : TimeTick Intent And Screen On
D/WeatherService( 2777): 2 : SDK version : 21
W/ActivityManager(  851): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2777): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2777): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2777): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2777): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2777): 2 : This is isUpdating : false
D/WeatherService( 2777): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2777): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2777): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2777): 2 : Fixed theme : optimus
,I/SystemConfig( 6052): existFile = false
I/SystemConfig( 6052): canReadFile = false
I/SystemConfig( 6052): systemFeature RCS result false
D/SystemConfig( 6052): refreshRcsSupport() :false
D/WeatherReflect( 2777): 2 : Map key string is -2
D/lim     ( 2777): 2 : time = 10:20
I/WeatherReflect( 2777): Model Name : LG-D722
D/WeatherTheme( 2777): 2 : Different view - status_min_formatted : 19 != 20
D/WeatherTheme( 2777): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2777): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2777): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2777): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2777): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2777): forecast size is 0
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2777): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2777): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2777): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2777): url is : null
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2777): 2 : update view, appWidgetId: 2
D/WeatherService( 2777): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 10:20:0
I/LockScreenSettings( 6074): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6074): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6074): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6074): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6074): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6074): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  851): Killing 4890:com.lge.drmservice/u0a51 (adj 15): empty #11
I/art     ( 5660): CheckpointMarkThreadRoots callback created = 0xaaf05300
I/art     ( 5660): CheckpointMarkThreadRoots callback created = 0xaaf055b0
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 61 ms] updated apps [took 61 ms] 
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  851): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6098 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  851): failed to open /acct/uid_10051/pid_4890/cgroup.procs: No such file or directory
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 10:20:00.507 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/WifiInternetCheck(  851): Single check msg out of sync, ignoring.
,D/Finsky  ( 6098): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ConnectivityService(  851): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  851): onReceive
D/LocSvc_java(  851): got connectivity action
D/LocSvc_java(  851): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  851): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  851): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  851): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  851): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  851): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  851): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
,V/AlarmManager(  851): ELAPSED_WAKEUP set : Alarm{f61e208 type 2 when 90267 com.android.providers.calendar} when 90267
I/[SystemUI]Clock( 1372): called onTimeUpdated()
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
,D/Finsky  ( 6098): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6098): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6098): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6098): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@189a3beb on behalf of 6098
D/Finsky  ( 6098): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6098): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6098): Skipping gmscore version check
D/Finsky  ( 6098): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5748): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/AudioManager( 5230): getMode name:com.lge.qremote
I/PackageBroadcastService( 5748): Null package name or gms related package.  Ignoreing.
I/AudioManager( 5230): getMode name:com.lge.qremote
,D/Finsky  ( 6098): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/SetupWizard( 5872): Connected to Gservices successfully
I/Icing   ( 5748): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  851): Killing 5605:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10014/pid_5605/cgroup.procs: No such file or directory
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/InputReader(  851): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
,I/System.out( 1730): propertyValue:false
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,E/MDM     ( 1730): [122] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5748): Restart initialization of location
I/DSQN    ( 5987): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5987): restart monitoring
I/DSQN    ( 5987): dsqn report finish
D/LGDataListener(  273): argv[0]=dsqncommand
D/LGDataListener(  273): argv[1]=wlan0
D/LGDataListener(  273): argv[2]=1
D/LGDataListener(  273): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  851): DSQM DsqnNotification wlan0  1
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/DSQN    (  851): start to monitor internet connection
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/administrator(  851): Handling package changes for user 0
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  851): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6162 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 33760(2MB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 13MB/22MB, paused 1.700ms total 176.660ms
,I/NotificationService(  851): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  851): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  851): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  851): Process com.android.contacts (pid 6052) has died
,I/BackupManagerService(  851): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/BackupManagerService(  851): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  851): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1d8e54d3
W/ResourcesManager(  851): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
,I/System.out(  851): propertyValue:false
W/ActivityManager(  851): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  851): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  851): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out(  851): propertyValue:false
V/WifiInternetCheck(  851): isHttpConnectionAvailable - We got a valid response : 204
,W/ResourceType(  851): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/Gmail   ( 6162): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6162): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ActivityManager(  851): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6162): Error finding the version of the Email provider.....
E/Gmail   ( 6162): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6162): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6162): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6162): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6162): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6162): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6162): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6162): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 6162): We do not support migrating this version of the Email provider.
I/ActivityManager(  851): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6201 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
W/ActivityManager(  851): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 22.693ms
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.728ms
,W/ActivityManager(  851): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 22.338ms
,I/art     (  851): Explicit concurrent mark sweep GC freed 80426(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.251ms total 253.469ms
I/Icing   ( 5748): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/LocationProviderProxy(  851): applying state to connected service
I/Gmail   ( 6162): Observing account changes for notifications
I/Gmail   ( 6162): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5748): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/ResourcesManager( 6201): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6201): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6201): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6201): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6201): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/Gmail   ( 6162): notifyAccountChanged
,I/Gmail   ( 6162): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6162): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6162): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6162): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/IndexDatabaseHelper( 6201): Using schema version: 115
I/Gmail   ( 6162): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/IndexDatabaseHelper( 6201): Index is fine
,V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/Gmail   ( 6162): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
I/ActivityManager(  851): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6228 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  851): Killing 6011:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_10011/pid_6011/cgroup.procs: No such file or directory
,I/PCSuite ( 6228): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6228): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
I/PCSuite ( 6228): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6228): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
I/PCSuite ( 6228): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6228): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
I/PCSuite ( 6228): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6228): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
I/ActivityManager(  851): Killing 6030:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10023/pid_6030/cgroup.procs: No such file or directory
,I/ActivityManager(  851): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6262 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6262): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6262): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6262): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@32203cf6, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@69118f7, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@76d1364, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@8b1e9cd, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@a8b3282, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@39344d93, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1d9a01d0, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3e0055c9, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@22bdf4ce, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@10cc2fef, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1f656afc, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3faf8585, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@22488fda, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1155dc0b, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@61c3ae8, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2b67f501, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@27afcfa6, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@37842de7, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@10ee1d94, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@36dde03d, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@22f94032, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2e5bc183, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@20597f00, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@4cd4339, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@cf72d7e, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@28ef2df, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1c578b2c, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@db5d9f5, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@754a38a, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2f99ddfb, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@11482e18, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@18572071, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@31616e56, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@229e5ed7, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2f9e13c4, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3dec52ad, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3d9e19e2, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@f001173, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1a4aa830, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@36286ca9, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1407f22e, lg_preferences_recent,_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@30c051cf,
D/GeneralPreferenceUtils( 6262): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/Config  ( 6262): [init]
,I/Config  ( 6262): LGCalendar ver.4.40.17
I/Config  ( 6262): start check model
I/Config  ( 6262): start check native_ca
I/Config  ( 6262): Config Operator=OPEN, Country=EU
D/Config  ( 6262): [setDefaultValuesToPref]
D/Config  ( 6262): [parseProfiles]
D/ProfilesParser( 6262): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6262): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6262): [updateProfiletoCountryInfo]
D/GeneralPreference( 6262): [checkAndMigrateOldPreference]
,I/ActivityManager(  851): Killing 6074:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/AlertReceiver( 6262): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
W/libprocessgroup(  851): failed to open /acct/uid_10069/pid_6074/cgroup.procs: No such file or directory
,I/InitNotificationRingtoneService( 6262): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6262): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 6262): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6262): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6262): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6262): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 6262): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6262): onHandleIntent
,D/HolidayDataLoader( 6262): readJsonAsset : holiday.json
D/AlertService( 6262): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6262): [updateWidgets] 
D/MonthWidgetProvider( 6262): [onReceive]
D/CalendarWidgetProvider( 6262): [onReceive]
D/CalendarWidgetProvider( 6262): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6262): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6262): [onReceive]
D/CalendarWidgetProvider( 6262): [onReceive]
D/CalendarWidgetProvider( 6262): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 6262): [onCreate] mContext.getPackageName() = com.android.calendar
V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6201): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
E/HolidayIntentService( 6262): onHandleIntent:holiday data empty
V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
I/PCSuite ( 6228): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6201): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6201): MCCMNC not supported: null
I/PCSuite ( 6228): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/UEI.SmartControl( 5981): Internal timer expired: 1
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  851): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6307 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  851): RTC_WAKEUP set : Alarm{6dfcc85 type 0 when 1455009604491 com.android.vending} when 1455009604491
,D/Finsky  ( 6098): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  851): android: cancelAsUser(2) by android
,D/libc-netbsd( 6098): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6098): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6098): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6098): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
,I/System.out( 6098): propertyValue:false
D/libc-netbsd( 6098): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6098): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/MusicStore( 6307): Database version: 120
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6307): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/libc-netbsd( 6098): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6098): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6307): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6307): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/jxcore-log( 5577): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5577): 
W/ResourcesManager( 6307): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6307): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6307): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 6307): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6307): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1bd5883e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6307): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6307): GMSCore installation verified
,I/ActivityManager(  851): Process com.google.android.apps.plus (pid 5660) has died
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ConfigStore( 6307): Config Database version: 1
,I/NotificationManager(  851): android: cancelAsUser(2) by android
,I/qtaguid ( 6098): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6098): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6098): untagSocket(41) failed with errno -22
D/Finsky  ( 6098): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/MediaRouter( 6307): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/MusicLeanback( 6307): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6307): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  851): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6341 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/NotificationManager(  851): android: cancelAsUser(2) by android
I/NetworkMonitor( 6307): type=WIFI subType= reason=null isConnected=true
,D/sensors_hal_Time(  851): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  851): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  851): tsOffsetIs: Apps: 95147378979; DSPS: 3209245; Offset : -2794190509
,I/ActivityManager(  851): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6367 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/AlarmManager(  851): RTC_WAKEUP set : Alarm{22ac42a8 type 0 when 1455009605677 com.google.android.googlequicksearchbox} when 1455009605677
,I/GHttpClientFactory( 6307): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6307): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6341): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6341): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/qtaguid ( 6098): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6098): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6098): untagSocket(41) failed with errno -22
I/MultiDex( 6341): VM with version 2.1.0 has multidex support
,I/MultiDex( 6341): install
I/MultiDex( 6341): VM has multidex support, MultiDex support library is disabled.
I/art     (  851): Explicit concurrent mark sweep GC freed 18469(940KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.458ms total 151.637ms
,W/ResourcesManager( 6367): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6367): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6367): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  851): Process com.google.android.talk (pid 5899) has died
,I/art     ( 5517): Explicit concurrent mark sweep GC freed 3100(123KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 429us total 43.108ms
,I/NotificationManager( 6307): com.google.android.music: cancel(1061) by com.google.android.music
V/JNIHelp ( 6341): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6341): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6341): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1ddeabc7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6341): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6341): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6341): com.google.android.gms: cancel(39789) by com.google.android.gms
I/LGEmail ( 6367): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/ChimeraCfgMgr( 6341): Reading stored module config
D/LGEmail ( 6367): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/art     ( 6098): CheckpointMarkThreadRoots callback created = 0xb056f2f0
D/ChimeraCfgMgr( 6341): Loading module com.google.android.gms.car from APK com.google.android.gms
I/art     ( 6098): CheckpointMarkThreadRoots callback created = 0xb056f2d0
,I/jxcore-log( 5577): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5577): 
D/NativeLibraryUtils( 6341): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  851): Process com.google.android.gm (pid 6162) has died
,D/CAR.SERVICE( 6341): Connecting to CarCallService...
,I/jxcore-log( 5577): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5577): 
I/jxcore-log( 5577): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5577): 
,I/art     ( 6341): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6341): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6341): com.google.android.projection.gearhead isn't installed.
,D/eas_req ( 6367): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/CAR.TEL.Service( 6341): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6341): Creating a new PhoneAdapter instance
I/jxcore-log( 5577): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5577): 
I/jxcore-log( 5577): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5577): 
,I/ActivityManager(  851): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6402 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/ActivityManager(  851): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6341): setListener: com.google.android.gms.car.dn@27783142
D/CAR.SERVICE( 6341): Package validated; name: com.android.vending
,W/ActivityManager(  851): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6341): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6341): Starting CarCallService with initial phone null
I/HubEmail( 6367): JNI_OnLoad()
I/HubEmail( 6367): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6367): registerNatives()
,I/HubEmail( 6367): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6367): registerNativeMethods()
I/HubEmail( 6367): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6367): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/NotificationManager( 6341): com.google.android.gms: cancel(10436) by com.google.android.gms
,W/Settings( 6367): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NotificationManager( 6098): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6098): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/ActivityManager(  851): Process com.android.settings (pid 6201) has died
,D/LGDMClient( 6402): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6402): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6402): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6402): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6402): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6402): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6402): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6402): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  851): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6431 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 6402): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6402): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6402): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6402): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6402): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6402): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  851): android: cancelAsUser(2) by android
I/AppUp4:AppBoxCP( 6431): onCreate
,W/AppUp4:DB( 6431):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6431):  setFingerPrint start
I/AppUp4:DB( 6431):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6431):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 6431):  SDK version = 0
I/AppUp4:DB( 6431):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6431): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6431): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6431): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6431): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6431): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6431): onReceive
I/AppUp4:CustModeStarterReceiver( 6431): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6431): Context : android.app.ReceiverRestrictedContext@a8b3282
D/AppUp4:CustFacade( 6431): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6431): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6431): begin check event
I/AppUp4:CustModeStarterReceiver( 6431): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6431): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6431): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6431): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6431): handleAsyncCustNotification do not startCustService
I/LgeMiscReceiver( 3162): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3162): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3162): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 5872): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5872): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 3230): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3230): DownloadService onCreate
,I/DownloadManager( 3230): in removeSpuriousFiles
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@3aaf4d48 on behalf of 3230
I/NotificationManager( 3230): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3230): in trimDatabase
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@33e007e1 on behalf of 3230
,I/ActivityManager(  851): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6453 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3230): DownloadService onStartCommand
I/qtaguid ( 6098): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6098): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6098): untagSocket(41) failed with errno -22
V/DownloadManager( 3230): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@330ff5f4 on behalf of 3230
,I/ActivityManager(  851): Killing 5981:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5230): android.os.DeadObjectException
,W/System.err( 5230): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5230): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5230): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5230): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5230): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5230): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5230): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5230): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5230): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5230): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5230): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5230): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5230): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5230): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5230): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5230): android.os.DeadObjectException
W/System.err( 5230): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5230): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5230): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5230): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5230): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5230): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5230): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5230): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5230): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5230): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5230): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5230): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5230): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5230): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5230): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/ResourcesManager( 6098): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6098): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6098): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  851): failed to open /acct/uid_10089/pid_5981/cgroup.procs: No such file or directory
W/ActivityManager(  851): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/WeatherAncestor( 2777): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:20:7
,I/ActivityManager(  851): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6481 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/DownloadManager( 3230): DownloadService onDestroy
D/UpdateThreadPoolManager( 2777): 2 : This is isUpdating : false
D/WeatherAncestor( 2777): connectivity changed - connection : true
D/Weather_cast( 2777): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2777): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:20:7
,D/WeatherService( 2777): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  851): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6498 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  851): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2777): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2777): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2777): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/Finsky  ( 6098): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  851): RTC_WAKEUP set : Alarm{710866f type 0 when 1455009607836 com.android.vending} when 1455009607836
D/UEI.SmartControl( 6481): Quickset Services start...
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
I/UEI.SmartControl( 6481): Manufacture = LGE
D/DeviceConnectionService( 1730): client connected with version: 8296000
,D/UEI.SmartControl( 6481): File observer start...
E/UEI.SmartControl( 6481): IR Port is disabled: false
,D/UEI.SmartControl( 6481): Starting file observer...
D/UEI.SmartControl( 6481): Extracting JNI libs...
D/UEI.SmartControl( 6481): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 6498): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  851): Process com.google.android.music:main (pid 6307) has died
,D/Finsky  ( 6098): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6098): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  851): Killing 6228:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6481): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6481): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6481): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/libprocessgroup(  851): failed to open /acct/uid_1000/pid_6228/cgroup.procs: No such file or directory
,I/UEI.SmartControl( 6481): --- Selecting new region: 2
I/UEI.SmartControl( 6481): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6481): Platform has CIR...
,D/UEI.SmartControl( 6481): NO CIR support, need to check package...
I/UEI.SmartControl( 6481): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6481): QS Service created
E/UEI.SmartControl( 6481): QS start get config
,D/UEI.SmartControl( 6481): Loading JNI Libs...
,D/UEI.SmartControl( 6481):  configuring local db...
I/Babel_SMS( 6498): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6498): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6498): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6498): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6498): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6498): MmsConfig.loadFromResources
E/Babel_SMS( 6498): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6498): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6498): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 6498): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6498): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6498): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6498): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6498): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6498): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6498): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6498): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6498): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6498): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6498): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6498): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6498): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6498): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6498): found sensor: Motion Accel, handle=46
I/art     ( 6498): CheckpointMarkThreadRoots callback created = 0xb042d880
,D/UEI.SmartControl( 6481):  ---- Has DB8: true
,D/UEI.SmartControl( 6481): QS start statue = true Error code = 0
D/UEI.SmartControl( 6481): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6481): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
I/art     ( 6498): CheckpointMarkThreadRoots callback created = 0xb042d860
D/UEI.SmartControl( 6481): IRRCDataComm has AudioManager!!!!.
W/Settings( 6498): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6498): startup - clean
W/irrc_jni( 6481): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6481): IrrcClient ++ 
D/irrcClient( 6481): getIrrcService ++ 
,D/irrcClient( 6481): getIrrcService -- 
D/irrcClient( 6481): IrrcClient -- 
W/irrc_jni( 6481): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6481): Services init done
I/UEI.SmartControl( 6481): Device manager: loading config....
D/UEI.SmartControl( 6481): QS Service init finished
,D/UEI.SmartControl( 6481): QS Service version name: 0.1.73
D/UEI.SmartControl( 6481): Config is loaded...
D/UEI.SmartControl( 6481): QS Service version code: 1073
D/UEI.SmartControl( 6481): Service requested: Control
D/UEI.SmartControl( 6481): -----IControl: 11
D/UEI.SmartControl( 6481): Internal service binding...
D/UEI.SmartControl( 6481): Caller: com.lge.qremote
D/UEI.SmartControl( 6481): ------------ IControl registerCallback...
I/UEI.SmartControl( 6481): Registering callback...
,D/UEI.SmartControl( 6481): -----IControl: 19
D/UEI.SmartControl( 6481): Caller: com.lge.qremote
I/UEI.SmartControl( 6481): Registering Services Ready callback...
I/UEI.SmartControl( 6481): Notify client services are ready...
D/UEI.SmartControl( 6481): -----IControl: 8
D/UEI.SmartControl( 6481): Caller: com.lge.qremote
I/Babel   ( 6498): deleted: false for 0
,D/UEI.SmartControl( 6481):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6481): Notify AllClients services are ready: 0
I/ActivityManager(  851): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6531 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  851): Killing 5230:com.lge.qremote/u0a106 (adj 15): empty #11
I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 22.555ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.017ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.530ms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  851): failed to open /acct/uid_10106/pid_5230/cgroup.procs: No such file or directory
,W/AudioCapabilities( 6498): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6498): Unsupported mime audio/adpcm
W/AudioCapabilities( 6498): Unsupported mime audio/g726
W/AudioCapabilities( 6498): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6498): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6498): Unsupported mime video/mjpg
W/VideoCapabilities( 6498): Unsupported mime video/theora
,W/AudioCapabilities( 6498): Unsupported mime audio/evrc
,W/AudioCapabilities( 6498): Unsupported mime audio/qcelp
W/VideoCapabilities( 6498): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6498): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6498): Unsupported mime audio/qcelp
W/AudioCapabilities( 6498): Unsupported mime audio/evrc
W/VideoCapabilities( 6498): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6498): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6498): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6498): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6498): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6498): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6498): onServiceConnected
W/Babel   ( 6498): Attempted to change video mute state without an active call.
I/NotificationManager( 6498): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6498): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6498): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6498): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6498): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  273): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 6498): propertyValue:false
I/Babel   ( 6498): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  851): Killing 6367:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_10021/pid_6367/cgroup.procs: No such file or directory
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6531): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6531): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6531): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6531): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6531): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6531):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6531):   adb logcat -s GAv4
,D/AlertService( 6262): Beginning updateAlertNotification
I/ActivityManager(  851): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6560 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
W/GAv4    ( 6531): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 6560): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/GAv4    ( 6531): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6531): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/CalendarProvider2( 6560): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2cc873b8
,D/CalendarProvider2( 6560): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6560): Created com.android.providers.calendar.CalendarAlarmManager@8b1e9cd(com.android.providers.calendar.CalendarProvider2@2cc873b8)
,D/AlertService( 6262): No fired or scheduled alerts
I/NotificationManager( 6262): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(3) by com.android.calendar
,I/NotificationManager( 6262): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(13) by com.android.calendar
,I/NotificationManager( 6262): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6262): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6262): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6262): No events found starting within 1 week.
,I/ActivityManager(  851): Killing 6262:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_10013/pid_6262/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/WebViewFactory( 6531): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6531): Time to load native libraries: 2 ms (timestamps 9404-9406)
I/LibraryLoader( 6531): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6531): Binding Chromium to main looper Looper (main, tid 1) {3d0414b7}
I/LibraryLoader( 6531): Expected native library version number "",actual native library version number ""
I/chromium( 6531): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6531): Initializing chromium process, singleProcess=true
W/art     ( 6531): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6531): ApplicationContext is null in ApplicationStatus
,W/chromium( 6531): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6531): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6531): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6531): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6531): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6531): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6531): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6531): Remote Branch: 
I/Adreno-EGL( 6531): Local Patches: 
I/Adreno-EGL( 6531): Reconstruct Branch: 
V/AudioPolicyService(  277): registerClient() client 0xb39b3f40, uid 10079
,W/AudioManagerAndroid( 6531): Requires BLUETOOTH permission
I/NSApplication( 6531): Starting up...
,I/ActivityManager(  851): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6632 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  851): Killing 6431:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  851): Killing 6402:com.lge.lgdmsclient/1000 (adj 15): empty #12
,W/libprocessgroup(  851): failed to open /acct/uid_10011/pid_6431/cgroup.procs: No such file or directory
,W/libprocessgroup(  851): failed to open /acct/uid_1000/pid_6402/cgroup.procs: No such file or directory
I/ActivityManager(  851): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6654 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  851): Killing 5872:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10038/pid_5872/cgroup.procs: No such file or directory
,W/ResourcesManager( 6654): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/iu.SyncManager( 5748): SYNC; picasa accounts
,D/NetworkLogImpl( 5748): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5748): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager(  851): Killing 6453:com.lge.drmservice/u0a51 (adj 15): empty #11
I/iu.UploadsManager( 5748): num queued entries: 0
I/iu.UploadsManager( 5748): num updated entries: 0
I/iu.SyncManager( 5748): NEXT; no task
,W/libprocessgroup(  851): failed to open /acct/uid_10051/pid_6453/cgroup.procs: No such file or directory
,I/ActivityManager(  851): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6687 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6687): Database version: 120
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/CAR.SERVICE( 6341): mConnectedToCar = false, abort
,E/ActivityThread( 6341): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1225f5db that was originally bound here
E/ActivityThread( 6341): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1225f5db that was originally bound here
E/ActivityThread( 6341): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6341): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6341): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6341): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6341): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6341): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6341): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6341): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6341): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6341): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6341): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6341): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6341): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6341): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6341): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6341): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6341): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6341): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6341): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6341): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6341): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6341): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6341): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6341): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@18ccab8d that was originally bound here
E/ActivityThread( 6341): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@18ccab8d that was originally bound here
E/ActivityThread( 6341): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6341): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6341): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6341): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6341): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6341): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6341): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6341): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6341): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6341): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6341): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6341): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6341): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6341): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6341): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6341): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6341): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6341): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6341): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6341): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6341): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6341): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  851): Unbind failed: could not find connection for android.os.BinderProxy@270e400e
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6687): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6687): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6687): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6687): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6687): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6687): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6687): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6687): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1bd5883e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6687): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6687): GMSCore installation verified
,I/ConfigStore( 6687): Config Database version: 1
,I/art     (  851): Explicit concurrent mark sweep GC freed 22284(1053KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.056ms total 158.797ms
,I/MediaRouter( 6687): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6687): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6687): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6687): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  851): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6718 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6687): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6687): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  851): Killing 6341:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10006/pid_6341/cgroup.procs: No such file or directory
I/NotificationManager( 6687): com.google.android.music: cancel(1061) by com.google.android.music
W/ResourcesManager( 6718): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6718): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6718): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/LGEmail ( 6718): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6718): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6718): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  851): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6755 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6718): JNI_OnLoad()
I/HubEmail( 6718): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6718): registerNatives()
I/HubEmail( 6718): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6718): registerNativeMethods()
I/HubEmail( 6718): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6718): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  851): Killing 6481:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
E/libprocessgroup(  851): failed to kill 1 processes for processgroup 6481
,W/Settings( 6718): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  851): Process com.google.android.apps.magazines (pid 6531) has died
,D/LGDMClient( 6755): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6755): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6755): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6755): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  851): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6776 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 6755): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6755): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6755): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6755): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,W/ContextImpl( 6755): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6755): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6755): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6755): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6755): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6755): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  268): 
I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/AppUp4:AppBoxCP( 6776): onCreate
,W/AppUp4:DB( 6776):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6776):  setFingerPrint start
I/AppUp4:DB( 6776):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6776):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 6776):  SDK version = 0
I/AppUp4:DB( 6776):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6776): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6776): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6776): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6776): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6776): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6776): onReceive
I/AppUp4:CustModeStarterReceiver( 6776): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6776): Context : android.app.ReceiverRestrictedContext@a8b3282
D/AppUp4:CustFacade( 6776): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6776): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6776): begin check event
I/AppUp4:CustModeStarterReceiver( 6776): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6776): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6776): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6776): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6776): handleAsyncCustNotification do not startCustService
I/ActivityManager(  851): Killing 6098:com.android.vending/u0a36 (adj 15): empty #11
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  851): failed to open /acct/uid_10036/pid_6098/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3162): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3162): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3162): networkInfo.isConnected() = false
I/ActivityManager(  851): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6810 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6810): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6810): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6810): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  851): Killing 6498:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_10061/pid_6498/cgroup.procs: No such file or directory
,V/DownloadManager( 3230): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3230): DownloadService onCreate
,I/DownloadManager( 3230): in removeSpuriousFiles
I/NotificationManager( 3230): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/ActivityManager(  851): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6833 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,D/PhoneMonitor( 6810): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/TelephonyAutoProfiling( 6810): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6810): [parse] Load xml
I/CheckinService( 5748): Checkin interval check for package: unspecified last checkin: 1455009591149 min interval config: 0 actual interval: 23553
,V/DownloadManager( 3230): DownloadService onStartCommand
V/DownloadManager( 3230): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/TelephonyAutoProfiling( 6810): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6810): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@2018d219 on behalf of 3230
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@1307d60 on behalf of 3230
,I/DownloadManager( 3230): in trimDatabase
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/PhoneMonitor( 6810): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@12eb42de on behalf of 3230
I/CheckinService( 5748): Checking schedule, now: 1455009614746 next: 1455009621109
I/CheckinService( 5748): active receiver: disabled
,V/DownloadManager( 3230): DownloadService onDestroy
,I/ActivityManager(  851): Killing 6560:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  851): failed to open /acct/uid_10014/pid_6560/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2777): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:20:14
D/UpdateThreadPoolManager( 2777): 2 : This is isUpdating : false
D/WeatherAncestor( 2777): connectivity changed - connection : true
D/Weather_cast( 2777): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2777): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:20:14
D/WeatherService( 2777): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  851): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6860 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  851): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2777): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2777): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2777): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6860): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/jxcore-log( 5577): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5577): 
,I/jxcore-log( 5577): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5577): 
,I/jxcore-log( 5577): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5577): 
,I/Babel_SMS( 6860): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6860): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6860): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6860): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6860): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6860): MmsConfig.loadFromResources
E/Babel_SMS( 6860): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6860): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6860): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6860): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6860): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6860): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6860): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6860): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6860): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6860): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6860): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6860): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6860): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6860): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6860): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6860): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6860): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6860): found sensor: Motion Accel, handle=46
,W/Settings( 6860): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6860): startup - clean
,I/Babel   ( 6860): deleted: false for 0
,I/art     ( 6860): CheckpointMarkThreadRoots callback created = 0xb042d920
I/art     ( 6860): CheckpointMarkThreadRoots callback created = 0xb042d8f0
,I/ActivityManager(  851): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6896 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.075ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.484ms
,W/AudioCapabilities( 6860): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6860): Unsupported mime audio/adpcm
W/AudioCapabilities( 6860): Unsupported mime audio/g726
,W/AudioCapabilities( 6860): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6860): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6860): Unsupported mime video/mjpg
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 23.115ms
,W/VideoCapabilities( 6860): Unsupported mime video/theora
,W/AudioCapabilities( 6860): Unsupported mime audio/evrc
W/AudioCapabilities( 6860): Unsupported mime audio/qcelp
W/VideoCapabilities( 6860): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6860): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6860): Unsupported mime audio/qcelp
W/AudioCapabilities( 6860): Unsupported mime audio/evrc
,W/VideoCapabilities( 6860): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6860): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6860): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6860): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6860): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6860): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6860): onServiceConnected
,W/Babel   ( 6860): Attempted to change video mute state without an active call.
D/libc-netbsd( 6860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  273): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/NotificationManager( 6860): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 6860): propertyValue:false
I/GAv4    ( 6896): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6896):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6896):   adb logcat -s GAv4
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6896): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 6896): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
I/Babel   ( 6860): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  851): Killing 6632:com.android.chrome/u0a48 (adj 15): empty #11
,W/ContextImpl( 6896): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6896): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/GAv4    ( 6896): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 6896): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6896): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  851): failed to open /acct/uid_10048/pid_6632/cgroup.procs: No such file or directory
,I/WebViewFactory( 6896): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6896): Time to load native libraries: 3 ms (timestamps 5763-5766)
I/LibraryLoader( 6896): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6896): Binding Chromium to main looper Looper (main, tid 1) {3d0414b7}
I/LibraryLoader( 6896): Expected native library version number "",actual native library version number ""
I/chromium( 6896): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6896): Initializing chromium process, singleProcess=true
W/art     ( 6896): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6896): ApplicationContext is null in ApplicationStatus
,W/chromium( 6896): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6896): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6896): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6896): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6896): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6896): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6896): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6896): Remote Branch: 
I/Adreno-EGL( 6896): Local Patches: 
I/Adreno-EGL( 6896): Reconstruct Branch: 
V/AudioPolicyService(  277): registerClient() client 0xb39b3f60, uid 10079
,W/AudioManagerAndroid( 6896): Requires BLUETOOTH permission
I/NSApplication( 6896): Starting up...
,I/ActivityManager(  851): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6960 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  851): Killing 6654:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/jxcore-log( 5577): Test app app.js loaded
I/jxcore-log( 5577): 
,W/libprocessgroup(  851): failed to open /acct/uid_10086/pid_6654/cgroup.procs: No such file or directory
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5577): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5577): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5577): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5577): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5577): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5577): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5577): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5577): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5577): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5577): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c9fa119 added. We now have 1 listener(s)
,D/BluetoothAdapterService(1040209353)( 1986): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37842de7
I/jxcore-log( 5577): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5577): 
,I/chromium( 5577): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  851): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6981 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  851): Killing 6687:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_10081/pid_6687/cgroup.procs: No such file or directory
,W/ResourcesManager( 6981): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  851): Killing 6718:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10021/pid_6718/cgroup.procs: No such file or directory
,I/ActivityManager(  851): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7008 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7008): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  851): Message: 20
D/BluetoothManagerService(  851): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f5598c1:true
,D/BluetoothAdapterService(1040209353)( 1986): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37842de7
D/BluetoothAdapterService(1040209353)( 1986): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37842de7
I/ActivityManager(  851): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7026 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7008): Create singleton instance
D/UEI.SmartControl( 7026): Quickset Services start...
,I/UEI.SmartControl( 7026): Manufacture = LGE
D/UEI.SmartControl( 7026): File observer start...
E/UEI.SmartControl( 7026): IR Port is disabled: false
D/UEI.SmartControl( 7026): Starting file observer...
D/UEI.SmartControl( 7026): Extracting JNI libs...
D/UEI.SmartControl( 7026): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7008): getMode name:com.lge.qremote
,I/ActivityManager(  851): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7045 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7026): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7026): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7026): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7026): --- Selecting new region: 2
,I/UEI.SmartControl( 7026): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7026): Platform has CIR...
D/UEI.SmartControl( 7026): NO CIR support, need to check package...
I/UEI.SmartControl( 7026): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7026): QS Service created
E/UEI.SmartControl( 7026): QS start get config
,I/MusicStore( 7045): Database version: 120
,D/UEI.SmartControl( 7026): Loading JNI Libs...
D/UEI.SmartControl( 7026):  configuring local db...
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7045): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/CheckinService( 5748): Done disabling old GoogleServicesFramework version
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7045): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7045): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/art     (  851): Explicit concurrent mark sweep GC freed 18952(924KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.294ms total 173.512ms
,W/ResourcesManager( 7045): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 7026):  ---- Has DB8: true
,V/JNIHelp ( 7045): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/UEI.SmartControl( 7026): QS start statue = true Error code = 0
D/UEI.SmartControl( 7026): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7026): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7026): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7026): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7026): IrrcClient ++ 
D/irrcClient( 7026): getIrrcService ++ 
,D/irrcClient( 7026): getIrrcService -- 
D/irrcClient( 7026): IrrcClient -- 
W/irrc_jni( 7026): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7026): Services init done
I/UEI.SmartControl( 7026): Device manager: loading config....
D/UEI.SmartControl( 7026): QS Service init finished
D/UEI.SmartControl( 7026): QS Service version name: 0.1.73
D/UEI.SmartControl( 7026): QS Service version code: 1073
,D/UEI.SmartControl( 7026): Service requested: Control
D/UEI.SmartControl( 7026): Config is loaded...
W/ActivityThread( 7045): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7045): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1bd5883e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7045): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7045): GMSCore installation verified
I/ConfigStore( 7045): Config Database version: 1
D/UEI.SmartControl( 7026): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7026):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 7026): Internal service binding...
I/UEI.SmartControl( 7026): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7026): -----IControl: 11
D/UEI.SmartControl( 7026): Caller: com.lge.qremote
D/UEI.SmartControl( 7026): ------------ IControl registerCallback...
I/UEI.SmartControl( 7026): Registering callback...
D/UEI.SmartControl( 7026): -----IControl: 19
D/UEI.SmartControl( 7026): Caller: com.lge.qremote
I/UEI.SmartControl( 7026): Registering Services Ready callback...
I/UEI.SmartControl( 7026): Notify client services are ready...
,D/UEI.SmartControl( 7026): -----IControl: 8
D/UEI.SmartControl( 7026): Caller: com.lge.qremote
I/ActivityManager(  851): Killing 6755:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_1000/pid_6755/cgroup.procs: No such file or directory
,I/MediaRouter( 7045): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7045): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7045): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  851): Killing 6776:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10011/pid_6776/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7045): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  851): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7090 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7045): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7045): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  851): Killing 6810:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/ResourcesManager( 7090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7090): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7090): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  851): failed to open /acct/uid_10038/pid_6810/cgroup.procs: No such file or directory
,I/NotificationManager( 7045): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7090): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7090): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7090): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  851): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7116 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7090): JNI_OnLoad()
I/HubEmail( 7090): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7090): registerNatives()
I/HubEmail( 7090): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7090): registerNativeMethods()
I/HubEmail( 7090): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7090): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  851): Killing 6833:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_10051/pid_6833/cgroup.procs: No such file or directory
,W/Settings( 7090): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7116): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7116): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7116): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7116): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7116): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7116): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 7116): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7116): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  851): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7140 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ContextImpl( 7116): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7116): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7116): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7116): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7116): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 7116): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  851): Killing 6860:com.google.android.talk/u0a61 (adj 15): empty #11
I/AppUp4:AppBoxCP( 7140): onCreate
,W/AppUp4:DB( 7140):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7140):  setFingerPrint start
I/AppUp4:DB( 7140):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7140):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7140):  SDK version = 0
I/AppUp4:DB( 7140):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  851): failed to open /acct/uid_10061/pid_6860/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 7140): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7140): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7140): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7140): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7140): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7140): onReceive
I/AppUp4:CustModeStarterReceiver( 7140): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7140): Context : android.app.ReceiverRestrictedContext@a8b3282
D/AppUp4:CustFacade( 7140): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7140): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7140): begin check event
I/AppUp4:CustModeStarterReceiver( 7140): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7140): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7140): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7140): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7140): handleAsyncCustNotification do not startCustService
I/ActivityManager(  851): Killing 6896:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_10079/pid_6896/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3162): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3162): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3162): networkInfo.isConnected() = true
,D/PhoneState( 3162): setPdpRejectCasuse : false
I/ActivityManager(  851): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7159 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7159): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7159): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7159): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  851): Killing 6960:com.android.chrome/u0a48 (adj 15): empty #11
D/PhoneMonitor( 7159): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7159): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7159): [parse] Load xml
,V/TelephonyAutoProfiling( 7159): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7159): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7159): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  851): failed to open /acct/uid_10048/pid_6960/cgroup.procs: No such file or directory
,V/DownloadManager( 3230): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3230): DownloadService onCreate
I/NotificationManager( 3230): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3230): in removeSpuriousFiles
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@29100f8c on behalf of 3230
I/DownloadManager( 3230): in trimDatabase
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@364aeea on behalf of 3230
I/ActivityManager(  851): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7181 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3230): DownloadService onStartCommand
V/DownloadManager( 3230): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@d749878 on behalf of 3230
I/CheckinService( 5748): Checkin interval check for package: unspecified last checkin: 1455009591149 min interval config: 0 actual interval: 28083
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/CheckinService( 5748): Checking schedule, now: 1455009619270 next: 1455009621109
I/CheckinService( 5748): active receiver: disabled
,V/DownloadManager( 3230): DownloadService onDestroy
,I/ActivityManager(  851): Killing 6981:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10086/pid_6981/cgroup.procs: No such file or directory
D/WeatherAncestor( 2777): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:20:19
,D/UpdateThreadPoolManager( 2777): 2 : This is isUpdating : false
D/WeatherAncestor( 2777): connectivity changed - connection : true
D/Weather_cast( 2777): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2777): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:20:19
D/WeatherService( 2777): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  851): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7208 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  851): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2777): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2777): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2777): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.172ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.029ms
,W/ResourcesManager( 7208): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.859ms
,I/Babel_SMS( 7208): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7208): MmsConfig.loadMmsSettings
I/Babel_SMS( 7208): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7208): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7208): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7208): MmsConfig.loadFromResources
E/Babel_SMS( 7208): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7208): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7208): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7208): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7208): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 7208): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7208): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7208): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7208): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7208): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7208): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7208): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7208): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7208): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7208): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7208): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7208): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7208): found sensor: Motion Accel, handle=46
W/Settings( 7208): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7208): startup - clean
I/Babel   ( 7208): deleted: false for 0
,I/art     ( 7208): CheckpointMarkThreadRoots callback created = 0xb042d920
,I/art     ( 7208): CheckpointMarkThreadRoots callback created = 0xb042d900
,I/ActivityManager(  851): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7239 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/AudioCapabilities( 7208): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7208): Unsupported mime audio/adpcm
W/AudioCapabilities( 7208): Unsupported mime audio/g726
W/AudioCapabilities( 7208): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7208): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7208): Unsupported mime video/mjpg
W/VideoCapabilities( 7208): Unsupported mime video/theora
,W/AudioCapabilities( 7208): Unsupported mime audio/evrc
W/AudioCapabilities( 7208): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7208): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7208): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7208): Unsupported mime audio/qcelp
W/AudioCapabilities( 7208): Unsupported mime audio/evrc
W/VideoCapabilities( 7208): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7208): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7208): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7208): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7208): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7208): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7208): onServiceConnected
W/Babel   ( 7208): Attempted to change video mute state without an active call.
,I/NotificationManager( 7208): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7208): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7208): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7208): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7208): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  273): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 7208): propertyValue:false
I/GAv4    ( 7239): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7239):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7239):   adb logcat -s GAv4
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7239): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7239): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7239): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 7239): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7239): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 7208): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  851): Killing 7008:com.lge.qremote/u0a106 (adj 15): empty #11
W/GAv4    ( 7239): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7239): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  851): failed to open /acct/uid_10106/pid_7008/cgroup.procs: No such file or directory
,I/WebViewFactory( 7239): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7239): Time to load native libraries: 3 ms (timestamps 9893-9896)
I/LibraryLoader( 7239): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7239): Binding Chromium to main looper Looper (main, tid 1) {3d0414b7}
I/LibraryLoader( 7239): Expected native library version number "",actual native library version number ""
I/chromium( 7239): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7239): Initializing chromium process, singleProcess=true
,W/art     ( 7239): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7239): ApplicationContext is null in ApplicationStatus
W/chromium( 7239): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7239): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7239): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7239): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7239): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7239): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7239): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7239): Remote Branch: 
I/Adreno-EGL( 7239): Local Patches: 
I/Adreno-EGL( 7239): Reconstruct Branch: 
V/AudioPolicyService(  277): registerClient() client 0xb39b3f80, uid 10079
W/AudioManagerAndroid( 7239): Requires BLUETOOTH permission
,I/NSApplication( 7239): Starting up...
I/ActivityManager(  851): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7311 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  851): Killing 7026:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_10089/pid_7026/cgroup.procs: No such file or directory
,I/ActivityManager(  851): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7334 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  851): Killing 7045:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_10081/pid_7045/cgroup.procs: No such file or directory
,W/ResourcesManager( 7334): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  851): Killing 7090:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10021/pid_7090/cgroup.procs: No such file or directory
,I/ActivityManager(  851): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7362 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7362): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 7362): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2cc873b8
,D/CalendarProvider2( 7362): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 7362): Created com.android.providers.calendar.CalendarAlarmManager@8b1e9cd(com.android.providers.calendar.CalendarProvider2@2cc873b8)
D/CalendarProviderBroadcastReceiver( 7362): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7362): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 7362): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 7362): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7362): [getOrCreateCalendarAlarmManager]
,I/ActivityManager(  851): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7381 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/CalendarProvider2( 7362): [IntentService] Release Lock
,D/CalendarProvider2( 7362): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  851): Killing 7116:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_1000/pid_7116/cgroup.procs: No such file or directory
,W/ResourcesManager( 7381): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/art     (  851): Explicit concurrent mark sweep GC freed 18995(906KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.593ms total 140.113ms
,D/BluetoothManagerService(  851): Message: 20
D/BluetoothManagerService(  851): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11e273e9:true
,D/BluetoothAdapterService(1040209353)( 1986): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37842de7
D/BluetoothAdapterService(1040209353)( 1986): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37842de7
I/AudioManager( 7381): getMode name:com.lge.qremote
,I/AudioManager( 7381): getMode name:com.lge.qremote
,I/AppUp4:CustModeStarterReceiver( 7140): onReceive
I/AppUp4:CustModeStarterReceiver( 7140): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7140): Context : android.app.ReceiverRestrictedContext@a8b3282
D/AppUp4:CustFacade( 7140): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7140): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7140): begin check event
I/AppUp4:CustModeStarterReceiver( 7140): Event For Nothing, skip.
V/AlarmManager(  851): RTC_WAKEUP set : Alarm{9c2bd7a type 0 when 1455009621109 com.google.android.gms} when 1455009621109
,I/ActivityManager(  851): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7401 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  851): RTC_WAKEUP set : Alarm{402092b type 0 when 1455009621787 com.android.vending} when 1455009621787
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  851): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7426 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationManager( 7208): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7208): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7208): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7426): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7426): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7426): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/JNIHelp ( 7208): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7208): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7208): Installed default security provider GmsCore_OpenSSL
D/Finsky  ( 7401): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/AppConfig( 7426): Total System Memory = 906309632
I/GalleryUtils( 7426): Application Heap = 96 MB
,I/AppConfig( 7426): App Tier : NOT_DEF
D/SystemHelper( 7426): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  851): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7461 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/Finsky  ( 7401): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7401): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7401): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7401): com.android.vending: cancel(-1050172287) by com.android.vending
W/ResourcesManager( 7461): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7461): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7461): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7461): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7461): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/Ads     ( 7401): Skipping gmscore version check
,D/Finsky  ( 7401): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7401): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@2856cfb6 on behalf of 7401
,D/Finsky  ( 7401): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/SystemConfig( 7461): BUILD Country: EU
I/SystemConfig( 7461): BUILD Operator: OPEN
,D/Finsky  ( 7401): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Finsky  ( 7401): [930] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7401): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  851): Killing 7159:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/ActivityManager(  851): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7494 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  851): Killing 7181:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  851): failed to open /acct/uid_10038/pid_7159/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/libprocessgroup(  851): failed to open /acct/uid_10051/pid_7181/cgroup.procs: No such file or directory
I/SystemConfig( 7461): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7461): existFile = false
I/SystemConfig( 7461): canReadFile = false
,I/SystemConfig( 7461): systemFeature RCS result false
D/SystemConfig( 7461): refreshRcsSupport() :false
I/LockScreenSettings( 7494): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7494): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7494): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7494): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7494): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7494): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  851): Killing 7239:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/art     ( 7334): CheckpointMarkThreadRoots callback created = 0xb042d610
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 54 ms] updated apps [took 54 ms] 
I/art     ( 7334): CheckpointMarkThreadRoots callback created = 0xb042d5f0
,W/libprocessgroup(  851): failed to open /acct/uid_10079/pid_7239/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 5748): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  851): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7519 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/PackageBroadcastService( 5748): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 5748): updateResources: need to parse f{com.google.android.gms}
,W/ActivityManager(  851): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7519): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 7519): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  851): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  851): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,E/Gmail   ( 7519): Error finding the version of the Email provider.....
E/Gmail   ( 7519): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7519): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7519): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7519): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7519): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7519): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7519): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7519): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7519): We do not support migrating this version of the Email provider.
W/ActivityManager(  851): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 7519): Observing account changes for notifications
,I/Gmail   ( 7519): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5748): Restart initialization of location
,E/MDM     ( 1730): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,D/Finsky  ( 7401): [935] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  851): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7583 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7381): Create singleton instance
,I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 347us total 34.522ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 21.883ms
,I/Gmail   ( 7519): notifyAccountChanged
I/Gmail   ( 7519): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 21.393ms
I/NotificationManager(  851): android: cancelAsUser(2) by android
,I/Gmail   ( 7519): getAccountsCursor
I/Gmail   ( 7519): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AudioManager( 7381): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7583): Quickset Services start...
I/Gmail   ( 7519): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7519): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/UEI.SmartControl( 7583): Manufacture = LGE
,D/UEI.SmartControl( 7583): File observer start...
E/UEI.SmartControl( 7583): IR Port is disabled: false
D/UEI.SmartControl( 7583): Starting file observer...
D/UEI.SmartControl( 7583): Extracting JNI libs...
D/UEI.SmartControl( 7583): --- this system supports 32-bit or 64-bit only
D/libc-netbsd( 7401): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7401): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7401): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7401): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager(  851): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7606 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
D/UEI.SmartControl( 7583): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7583): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7583): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 7401): propertyValue:false
I/UEI.SmartControl( 7583): --- Selecting new region: 2
,I/UEI.SmartControl( 7583): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7583): Platform has CIR...
D/UEI.SmartControl( 7583): NO CIR support, need to check package...
I/UEI.SmartControl( 7583): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7583): QS Service created
,E/UEI.SmartControl( 7583): QS start get config
,D/UEI.SmartControl( 7583): Loading JNI Libs...
,D/UEI.SmartControl( 7583):  configuring local db...
D/PhoneMonitor( 7606): Register our PhoneStateListener
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AudioManager( 7381): getMode name:com.lge.qremote
D/PhoneMonitor( 7606): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 7606): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7606): [parse] Load xml
V/TelephonyAutoProfiling( 7606): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7606): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/AudioManager( 7381): getMode name:com.lge.qremote
D/PhoneMonitor( 7606): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/CheckinService( 5748): Checkin interval check for package: unspecified last checkin: 1455009591149 min interval config: 0 actual interval: 33099
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AudioManager( 7381): getMode name:com.lge.qremote
I/CheckinService( 5748): Checking schedule, now: 1455009624288 next: 1455009621109
I/CheckinService( 5748): active receiver: enabled
,I/art     (  851): Explicit concurrent mark sweep GC freed 19857(876KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.540ms total 170.324ms
,I/CheckinService( 5748): Preparing to send checkin request
I/CheckinService( 5748): Checkin interval check for package: unspecified last checkin: 1455009591149 min interval config: 0 actual interval: 33177
I/EventLogService( 5748): Accumulating logs since 1455009581059
,I/Gmail   ( 7519): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 3598): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  851): Killing 7311:com.android.chrome/u0a48 (adj 15): empty #11
,I/Icing   ( 5748): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/UEI.SmartControl( 7583):  ---- Has DB8: true
D/UEI.SmartControl( 7583): QS start statue = true Error code = 0
D/UEI.SmartControl( 7583): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 7583): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7583): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7583): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7583): IrrcClient ++ 
D/irrcClient( 7583): getIrrcService ++ 
,D/irrcClient( 7583): getIrrcService -- 
D/irrcClient( 7583): IrrcClient -- 
W/irrc_jni( 7583): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7583): Services init done
I/UEI.SmartControl( 7583): Device manager: loading config....
D/UEI.SmartControl( 7583): Config is loaded...
,D/UEI.SmartControl( 7583):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7583): Notify AllClients services are ready: 0
W/libprocessgroup(  851): failed to open /acct/uid_10048/pid_7311/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7583): QS Service init finished
D/UEI.SmartControl( 7583): QS Service version name: 0.1.73
D/UEI.SmartControl( 7583): QS Service version code: 1073
D/UEI.SmartControl( 7583): Service requested: Control
D/UEI.SmartControl( 7583): Internal service binding...
D/UEI.SmartControl( 7583): -----IControl: 11
D/UEI.SmartControl( 7583): Caller: com.lge.qremote
D/UEI.SmartControl( 7583): ------------ IControl registerCallback...
I/UEI.SmartControl( 7583): Registering callback...
D/UEI.SmartControl( 7583): -----IControl: 19
,D/UEI.SmartControl( 7583): Caller: com.lge.qremote
I/UEI.SmartControl( 7583): Registering Services Ready callback...
I/UEI.SmartControl( 7583): Notify client services are ready...
D/UEI.SmartControl( 7583): -----IControl: 8
I/CheckinRequestBuilder( 5748): Checkin reason type: 8 attempt count: 1
D/UEI.SmartControl( 7583): Caller: com.lge.qremote
I/AudioManager( 7381): getMode name:com.lge.qremote
,E/ActivityThread( 5748): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  851): Killing 7140:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/Icing   ( 5748): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  851): Killing 7362:com.android.providers.calendar/u0a14 (adj 15): empty #12
W/libprocessgroup(  851): failed to open /acct/uid_10011/pid_7140/cgroup.procs: No such file or directory
W/libprocessgroup(  851): failed to open /acct/uid_10014/pid_7362/cgroup.procs: No such file or directory
,I/AudioManager( 7381): getMode name:com.lge.qremote
,I/AudioManager( 7381): getMode name:com.lge.qremote
,I/art     ( 5517): Explicit concurrent mark sweep GC freed 2147(81KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 787us total 35.324ms
,I/ActivityManager(  851): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7651 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 7651): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7651): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7651): VM with version 2.1.0 has multidex support
I/MultiDex( 7651): install
I/MultiDex( 7651): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7651): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7651): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7651): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1ddeabc7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7651): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7651): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7651): com.google.android.gms: cancel(39789) by com.google.android.gms
E/MDM     ( 1730): [122] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5748): Restart initialization of location
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 1730): location=null
I/art     ( 7651): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7651): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/NativeLibraryUtils( 7651): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): CdmEngine::OpenSession
I/WVCdm   (  277): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  277): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  277): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  277): L1 library not specified. Falling Back to L3
,D/sensors_hal_Time(  851): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  851): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  851): tsOffsetIs: Apps: 115150055429; DSPS: 3864693; Offset : -2794199944
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  277): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  277): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
D/WVCdm   (  277): PrepareKeyRequest: nonce=3984389002
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     ( 7651): CheckpointMarkThreadRoots callback created = 0xaaf11500
,I/art     ( 7651): CheckpointMarkThreadRoots callback created = 0xaaf114e0
,I/dex2oat ( 7687): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7687): dex2oat took 125.453ms (threads: 4)
,I/Adreno-EGL( 7651): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7651): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7651): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7651): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7651): Remote Branch: 
I/Adreno-EGL( 7651): Local Patches: 
I/Adreno-EGL( 7651): Reconstruct Branch: 
,I/WVCdm   (  277): CdmEngine::OpenSession
,I/MusicWidget( 2710): mDelayedStopHandler : unbind
,I/MusicBrowser( 2792): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2792): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2792): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2792): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2792): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2792): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2792): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2792): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  851):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@20597f00com.lge.music.MediaPlaybackService$6@4cd4339
D/MusicBrowser( 2792): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@22bdf4ce
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,I/MusicBrowser( 2792): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2792): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2792): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2792): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2792): reset
V/MediaPlayer[Native]( 2792): setListener
V/MediaPlayer[Native]( 2792): disconnect
V/MediaPlayer[Native]( 2792): destructor
,V/AudioFlinger(  277): releasing 19 from 2792 for -1
V/AudioFlinger(  277):  decremented refcount to 0
V/AudioFlinger(  277): purging stale effects
V/MediaPlayer[Native]( 2792): disconnect
D/MusicBrowser( 2792): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2792): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2792): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2792): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2792): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2792): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2792): [SmartShareManagerClient] unregisterListener: 217525630
W/SmartShareClient( 2792): [SmartShareManagerClient] unregisterListener invalid listener: 217525630
I/SmartShareClient( 2792): [SmartShareManagerClient] terminate service: 2792/MediaPlaybackService/124588900
E/HomeCloudIF( 2792): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2792): [SmartShareManagerClient] unbindService context:android.app.Application@28ef2df
V/CloudHub( 2792): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2792): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2792): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2792): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2792): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  851): Killing 7426:com.android.gallery3d/u0a23 (adj 15): empty #11
I/CloudHub( 2792): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
W/libprocessgroup(  851): failed to open /acct/uid_10023/pid_7426/cgroup.procs: No such file or directory
,I/ActivityManager(  851): Killing 7461:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10018/pid_7461/cgroup.procs: No such file or directory
,I/WVCdm   (  277): CdmEngine::CloseSession
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  277): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  277): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
D/WVCdm   (  277): PrepareKeyRequest: nonce=2354488544
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/GAv4-SVC( 5748): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 7519): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,D/UEI.SmartControl( 7583): Internal timer expired: 1
,I/WVCdm   (  277): CdmEngine::CloseSession
,I/WVCdm   (  277): L3 Terminate.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Adreno-EGL( 7651): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7651): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7651): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7651): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7651): Remote Branch: 
I/Adreno-EGL( 7651): Local Patches: 
I/Adreno-EGL( 7651): Reconstruct Branch: 
,I/Adreno-EGL( 7651): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7651): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7651): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7651): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7651): Remote Branch: 
I/Adreno-EGL( 7651): Local Patches: 
I/Adreno-EGL( 7651): Reconstruct Branch: 
,I/CheckinRequestBuilder( 5748): Classify the device as Phone.
,D/libc-netbsd( 5748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 5748): propertyValue:false
D/libc-netbsd( 5748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5748): Sending checkin request (9766 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinRequestBuilder( 5748): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5748): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 5748): Classify the device as Phone.
,I/CheckinTask( 5748): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5748): Checking schedule, now: 1455009631410 next: 1455536880405
I/CheckinService( 5748): active receiver: disabled
,I/CheckinService( 5748): Checking schedule, now: 1455009631444 next: 1455536880405
I/CheckinService( 5748): active receiver: disabled
,D/CheckinService( 5748): Recording last checkin time for package unspecified as 1455009631453
,I/ActivityManager(  851): Killing 7494:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10069/pid_7494/cgroup.procs: No such file or directory
,V/SetupWizard( 7606): Connected to Gservices successfully
,I/ActivityManager(  851): Killing 7334:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10086/pid_7334/cgroup.procs: No such file or directory
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  851): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/administrator(  851): Handling package changes for user 0
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/ActivityManager(  851): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7748 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationManager( 7208): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7208): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7208): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 7748): onCreate
,W/AppUp4:DB( 7748):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7748):  setFingerPrint start
I/AppUp4:DB( 7748):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7748):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7748):  SDK version = 0
,I/AppUp4:DB( 7748):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7748): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7748): onReceive
I/AppUp4:CustModeStarterReceiver( 7748): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7748): Context : android.app.ReceiverRestrictedContext@69118f7
D/AppUp4:CustFacade( 7748): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7748): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7748): begin check event
I/AppUp4:CustModeStarterReceiver( 7748): Event For Nothing, skip.
I/ActivityManager(  851): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7774 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationService(  851): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  851): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  851): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  851): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  851): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  851): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3a85cfe0
W/ResourcesManager(  851): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7774): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7774): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7774): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/ActivityManager(  851): Process com.android.vending (pid 7401) has died
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
W/ResourceType(  851): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  851): Process com.google.android.gm (pid 7519) has died
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/AppConfig( 7774): Total System Memory = 906309632
,I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/GalleryUtils( 7774): Application Heap = 96 MB
I/AppConfig( 7774): App Tier : NOT_DEF
,D/LocationProviderProxy(  851): applying state to connected service
D/SystemHelper( 7774): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  851): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7797 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7797): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7797): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7797): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7797): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7797): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/AudioFlinger(  277): 2792 died, releasing its sessions
,V/AudioFlinger(  277):  pid 1748 @ 0
V/AudioFlinger(  277):  pid 3162 @ 1
V/AudioFlinger(  277):  pid 3162 @ 2
I/ActivityManager(  851): Process com.lge.music (pid 2792) has died
,I/art     (  851): Explicit concurrent mark sweep GC freed 25291(1320KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 1.854ms total 161.373ms
,I/SystemConfig( 7797): BUILD Country: EU
I/SystemConfig( 7797): BUILD Operator: OPEN
,I/ActivityManager(  851): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7818 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7797): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7797): existFile = false
I/SystemConfig( 7797): canReadFile = false
I/SystemConfig( 7797): systemFeature RCS result false
,D/SystemConfig( 7797): refreshRcsSupport() :false
,I/LockScreenSettings( 7818): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7818): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7818): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7818): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7818): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7818): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  851): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7838 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  851): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7866 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
,I/ActivityManager(  851): Killing 7583:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7381): android.os.DeadObjectException
,W/System.err( 7381): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7381): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7381): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7381): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7381): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7381): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7381): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7381): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7381): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7381): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7381): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7381): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7381): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7381): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7381): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7381): android.os.DeadObjectException
W/System.err( 7381): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7381): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7381): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7381): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7381): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7381): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7381): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7381): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7381): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7381): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7381): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7381): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7381): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7381): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7381): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,W/libprocessgroup(  851): failed to open /acct/uid_10089/pid_7583/cgroup.procs: No such file or directory
,W/ActivityManager(  851): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  851): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7883 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7883): Quickset Services start...
,I/UEI.SmartControl( 7883): Manufacture = LGE
D/UEI.SmartControl( 7883): File observer start...
E/UEI.SmartControl( 7883): IR Port is disabled: false
D/UEI.SmartControl( 7883): Starting file observer...
D/UEI.SmartControl( 7883): Extracting JNI libs...
D/UEI.SmartControl( 7883): --- this system supports 32-bit or 64-bit only
D/Finsky  ( 7866): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 7883): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7883): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7883): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7883): --- Selecting new region: 2
,I/UEI.SmartControl( 7883): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7883): Platform has CIR...
D/UEI.SmartControl( 7883): NO CIR support, need to check package...
I/UEI.SmartControl( 7883): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7883): QS Service created
,E/UEI.SmartControl( 7883): QS start get config
,D/UEI.SmartControl( 7883): Loading JNI Libs...
,D/UEI.SmartControl( 7883):  configuring local db...
D/Finsky  ( 7866): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7866): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7866): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7866): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@3d0414b7 on behalf of 7866
D/Finsky  ( 7866): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7866): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7866): Skipping gmscore version check
D/Finsky  ( 7866): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5748): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5748): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5748): updateResources: need to parse f{com.google.android.gms}
D/Finsky  ( 7866): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/UEI.SmartControl( 7883):  ---- Has DB8: true
,D/UEI.SmartControl( 7883): QS start statue = true Error code = 0
D/UEI.SmartControl( 7883): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7883): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7883): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7883): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7883): IrrcClient ++ 
D/irrcClient( 7883): getIrrcService ++ 
,D/irrcClient( 7883): getIrrcService -- 
D/irrcClient( 7883): IrrcClient -- 
W/irrc_jni( 7883): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7883): Services init done
I/UEI.SmartControl( 7883): Device manager: loading config....
D/UEI.SmartControl( 7883): QS Service init finished
D/UEI.SmartControl( 7883): QS Service version name: 0.1.73
D/UEI.SmartControl( 7883): QS Service version code: 1073
D/UEI.SmartControl( 7883): Config is loaded...
,D/UEI.SmartControl( 7883): Service requested: Control
I/ActivityManager(  851): Killing 7381:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7883): -----IControl: 11
D/UEI.SmartControl( 7883): Caller: com.lge.qremote
D/UEI.SmartControl( 7883): ------------ IControl registerCallback...
I/UEI.SmartControl( 7883): Registering callback...
D/UEI.SmartControl( 7883):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7883): Notify AllClients services are ready: 0
,W/libprocessgroup(  851): failed to open /acct/uid_10106/pid_7381/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7883): Internal service binding...
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1986): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  851): battery changed pluggedType: 2
,D/charger_monitor(  474): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/Icing   ( 5748): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5748): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  851): Killing 7606:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10038/pid_7606/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  851): Killing 7651:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  851): failed to open /acct/uid_10006/pid_7651/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7883): Internal timer expired: 1
,D/UEI.SmartControl( 7883): Service.onUnbind: IControl
D/UEI.SmartControl( 7883): Service.onDestroy
D/UEI.SmartControl( 7883): Shutdown IRRCPlayer... 
,W/irrc_jni( 7883): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7883): ~IrrcClient ++ 
D/irrcClient( 7883): ~IrrcClient -- 
W/irrc_jni( 7883): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7883): Blaster closed
,D/UEI.SmartControl( 7883): Blaster closed
D/UEI.SmartControl( 7883): Shut down QS...
D/UEI.SmartControl( 7883): Stopped file observer...
I/UEI.SmartControl( 7883): QS lib stop result = true
D/UEI.SmartControl( 7883): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  851): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  851): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  851): tsOffsetIs: Apps: 135150867246; DSPS: 4520080; Offset : -2794212232
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  851): ELAPSED_WAKEUP set : Alarm{21fb0e21 type 2 when 146320 com.google.android.gms} when 146320
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1730): Vacuum at: now=1455009657006 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  851): ALS enabled for SRE
,D/PowerManagerServiceEx(  851): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29378 ms ago)
D/qdlights(  851): set_light_backlight: 252
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  851): set_light_backlight: 248
D/qdlights(  851): set_light_backlight: 245
,D/qdlights(  851): set_light_backlight: 242
,D/qdlights(  851): set_light_backlight: 238
,D/qdlights(  851): set_light_backlight: 235
,D/qdlights(  851): set_light_backlight: 232
,D/qdlights(  851): set_light_backlight: 228
,D/PowerManagerServiceEx(  851): acquireWakeLockInternal: lock=438850590, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=851
D/WeatherService( 2777): 2 : TimeTick Intent has been received, Time(hour:min:sec) 10:21:0
,D/qdlights(  851): set_light_backlight: 225
D/WeatherService( 2777): 2 : TimeTick Intent And Screen On
D/WeatherService( 2777): 2 : SDK version : 21
W/ActivityManager(  851): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2777): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2777): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2777): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2777): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2777): 2 : This is isUpdating : false
D/WeatherService( 2777): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2777): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2777): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2777): 2 : Fixed theme : optimus
D/qdlights(  851): set_light_backlight: 222
,D/WeatherReflect( 2777): 2 : Map key string is -2
D/qdlights(  851): set_light_backlight: 218
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
D/lim     ( 2777): 2 : time = 10:21
I/WeatherReflect( 2777): Model Name : LG-D722
D/WeatherTheme( 2777): 2 : Different view - status_min_formatted : 20 != 21
D/WeatherTheme( 2777): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,I/[SystemUI]Clock( 1372): called onTimeUpdated()
D/qdlights(  851): set_light_backlight: 215
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/WeatherReflect( 2777): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2777): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/qdlights(  851): set_light_backlight: 212
D/qdlights(  851): set_light_backlight: 208
,D/qdlights(  851): set_light_backlight: 205
,D/qdlights(  851): set_light_backlight: 202
,D/Weather4x2_optimus( 2777): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2777): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2777): forecast size is 0
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2777): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2777): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2777): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2777): url is : null
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2777): 2 : update view, appWidgetId: 2
D/WeatherService( 2777): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 10:21:0
,D/qdlights(  851): set_light_backlight: 198
D/PowerManagerServiceEx(  851): releaseWakeLockInternal: lock=438850590 [*alarm*], flags=0x0
,D/qdlights(  851): set_light_backlight: 195
D/qdlights(  851): set_light_backlight: 192
,D/qdlights(  851): set_light_backlight: 188
,D/qdlights(  851): set_light_backlight: 185
,D/qdlights(  851): set_light_backlight: 182
,D/qdlights(  851): set_light_backlight: 178
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/qdlights(  851): set_light_backlight: 175
D/qdlights(  851): set_light_backlight: 172
,D/qdlights(  851): set_light_backlight: 168
,D/qdlights(  851): set_light_backlight: 165
,D/qdlights(  851): set_light_backlight: 162
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
D/qdlights(  851): set_light_backlight: 158
,D/qdlights(  851): set_light_backlight: 155
,D/qdlights(  851): set_light_backlight: 152
,D/qdlights(  851): set_light_backlight: 148
,D/qdlights(  851): set_light_backlight: 145
,D/qdlights(  851): set_light_backlight: 142
,D/qdlights(  851): set_light_backlight: 138
,D/qdlights(  851): set_light_backlight: 135
,D/qdlights(  851): set_light_backlight: 132
,D/qdlights(  851): set_light_backlight: 128
,D/qdlights(  851): set_light_backlight: 125
,D/qdlights(  851): set_light_backlight: 122
,D/qdlights(  851): set_light_backlight: 118
,D/qdlights(  851): set_light_backlight: 115
,D/qdlights(  851): set_light_backlight: 112
,D/qdlights(  851): set_light_backlight: 108
,D/qdlights(  851): set_light_backlight: 105
,D/qdlights(  851): set_light_backlight: 102
,D/qdlights(  851): set_light_backlight: 98
,D/qdlights(  851): set_light_backlight: 95
,D/qdlights(  851): set_light_backlight: 92
,D/qdlights(  851): set_light_backlight: 88
,D/qdlights(  851): set_light_backlight: 85
,D/qdlights(  851): set_light_backlight: 82
,D/qdlights(  851): set_light_backlight: 78
,D/qdlights(  851): set_light_backlight: 75
,D/qdlights(  851): set_light_backlight: 72
,D/qdlights(  851): set_light_backlight: 68
,D/qdlights(  851): set_light_backlight: 65
,D/qdlights(  851): set_light_backlight: 62
,D/qdlights(  851): set_light_backlight: 58
,D/qdlights(  851): set_light_backlight: 55
,D/qdlights(  851): set_light_backlight: 52
,D/qdlights(  851): set_light_backlight: 48
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  851): set_light_backlight: 45
,D/qdlights(  851): set_light_backlight: 42
,D/qdlights(  851): set_light_backlight: 38
,D/qdlights(  851): set_light_backlight: 35
,D/qdlights(  851): set_light_backlight: 32
,D/qdlights(  851): set_light_backlight: 28
,D/qdlights(  851): set_light_backlight: 25
,D/qdlights(  851): set_light_backlight: 22
,D/qdlights(  851): set_light_backlight: 18
,D/qdlights(  851): set_light_backlight: 15
,D/qdlights(  851): set_light_backlight: 12
,D/qdlights(  851): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/sensors_hal_Time(  851): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  851): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  851): tsOffsetIs: Apps: 155151608123; DSPS: 5175464; Offset : -2794203673
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  851): ALS enabled for SRE
D/PowerManagerServiceEx(  851): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36374 ms ago)
I/PowerManagerService(  851): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  851): ALS enabled for SRE
D/PowerManagerServiceEx(  851): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36387 ms ago)
,W/ContextImpl(  851): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  851): Sleeping (uid 1000)...
D/LPWGController(  851): [updateScreenState] screen on = false
D/LPWGController(  851): disable proximity sensor
,D/LPWGController(  851): enable proximity sensor
I/SensorManager(  851): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1a0124ff] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  851): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  851): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  851): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  851): activate: handle is 48, enable
V/sensors_hal_Ctx(  851): activate sensors is 1400000000000
D/sensors_hal_Thresh(  851): enable: handle=48
I/sensors_hal_SAM(  851): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  851): waitForResponse: timeout=1000
V/sensors_hal_SAM(  851): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  851): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  851): enable: Received response: 0
D/PowerManagerServiceEx(  851): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36430 ms ago)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Adreno-EGL(  851): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  851): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  851): Build Date: 03/02/15 Mon
I/Adreno-EGL(  851): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  851): Remote Branch: 
I/Adreno-EGL(  851): Local Patches: 
I/Adreno-EGL(  851): Reconstruct Branch: 
,D/PermissionCache(  243): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1156 us)
,I/Sensors (  406): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  851): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  851): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  851): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  851): processInd: handle 48, count=1
V/sensors_hal_Thresh(  851): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  851): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  851): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  851): poll: count: 256
I/sensors_hal_Ctx(  851): poll: released wakelock sensor_ind
D/sensors_hal_Util(  851): waitForResponse: timeout=0
D/LPWGController(  851): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  851): current mode = 1  value = 1 1
I/LPWGController(  851): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  851): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  851): set_light_backlight: 0
,I/SensorManager(  851): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  851): activate: handle is 46, disable
V/sensors_hal_Ctx(  851): activate sensors is 1000000000000
D/sensors_hal_LP2(  851): enable: handle=46
D/sensors_hal_LP2(  851): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  851): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  243): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  243): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  851): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  851): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  851): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  851): Display changed displayId=0
,D/DSDPConnection( 1748): Display #0 changed.
,D/qdhwcomposer(  243): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  851): Excessive delay in setPowerMode(): 171ms
I/qdhwcomposer(  243): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  851): Got set_interactive hint
,D/KeyguardViewMediator( 1372): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
,D/KeyguardViewMediator( 1372): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
D/KeyguardViewMediator( 1372): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1372): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1372): unregisterProximitySensor
,D/WifiServerServiceExt(  851): sendKtScanInterval  mRtspPlay : false
,D/StatusBarWindowView( 1372): onScreenTurnedOff why = 3
V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=on, calling pid 851
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: enter: screen_state=on
V/compress_voip(  277): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  277): voice_extn_compress_voip_set_parameters: exit
V/voice   (  277): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  277): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  277): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  277): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  277): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  277): adev_set_parameters: exit with code(0)
,D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/WifiServerServiceExt(  851): set CMD_KT_SCAN_INTERVAL
,D/GpsLocationProvider(  851): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:true
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1801): lockStatus = 0
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1784): action : android.intent.action.SCREEN_ON
I/LEDService( 1801): updateLightsLocked : turn off led
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1801): RESTART MSG
,D/NfcServiceNXP( 1784): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1784): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 3
D/NfcService( 1784): Discovery configuration equal, not updating.
D/SplitWindow(  851): check instance of lgWin Window{3181942a u0 SearchPanel}
,D/Ulp_jni (  851): JNI:system_update. Event-0
,D/InputDispatcher(  851): Window went away: Window{2cbf1548 u0 SearchPanel}
,I/[SystemUI]Clock( 1372): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 42169(2MB) AllocSpace objects, 33(528KB) LOS objects, 39% free, 13MB/22MB, paused 1.697ms total 104.990ms
,I/Sensors (  406): sns_pwr.c(301):releasing wakelock
D/WeatherService( 2777): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:21:8
,D/WeatherService( 2777): 2 : ACTION screen on
D/WeatherService( 2777): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2777): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2777): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:21:8
,W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): ACTION_SCREEN_ON
D/AppCleanupService( 4058): android.intent.action.SCREEN_ON
,V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=off, calling pid 851
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: enter: screen_state=off
V/compress_voip(  277): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  277): voice_extn_compress_voip_set_parameters: exit
V/voice   (  277): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  277): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  277): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  277): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  277): adev_set_parameters: exit with code(0)
D/WifiController(  851): CMD_SCREEN_OFF 
D/WifiController(  851): shouldWifiStayAwake TRUE
,D/GpsLocationProvider(  851): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:false
,I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1801): clear
I/LEDService( 1801): updateLightsLocked : turn on led
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
E/LEDService( 1801): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1801): Can't handle this request of patternId:0
D/LEDHandler( 1801): RESTART MSG
D/LNfcService( 1784): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1784): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1875): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2777): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:21:8
D/WeatherService( 2777): 2 : ACTION screen off
D/WeatherService( 2777): 2 : TimeTick Receiver Unregister
D/WeatherService( 2777): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:21:8
,W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  851): ACTION_SCREEN_OFF
D/AppCleanupService( 4058): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4058): AppUsageStatsSaveTask
,E/NxpNfcJni( 1784): getReconnectState = 0x0
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/LNfcService( 1784): isRequireNfcCRouting() return true
,D/LNfcService( 1784): isHCERoutingtoHost() return : true
D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: 0
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 1
E/NxpNfcJni( 1784): getReconnectState = 0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  851): ELAPSED_WAKEUP set : Alarm{11cd121b type 2 when 162285 com.android.systemui} when 162285
,D/KeyguardViewMediator( 1372): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1748): getCallState : 0
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1372): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1372): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  851): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  851): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  851): tsOffsetIs: Apps: 175152282335; DSPS: 5830846; Offset : -2794200613
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  851): ELAPSED_WAKEUP set : Alarm{2bb71fb8 type 2 when 182761 android} when 182761
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1986): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  851): battery changed pluggedType: 2
V/AlarmManager(  851): ELAPSED_WAKEUP set : Alarm{28f2c191 type 2 when 188315 com.google.android.gms} when 188315
,I/PhenotypeConfigurator( 1730): Scheduling Phenotype for one-off execution 923 seconds from now (1455009699128)
,D/GetConfigurationSnapshotOperation( 1730): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1730): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1730): Using platform SSLCertificateSocketFactory
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/LocationManagerService(  851): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  851): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  851): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  851): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  851): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  851): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  851): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  851): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  851): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  851): tsOffsetIs: Apps: 195153010243; DSPS: 6486230; Offset : -2794205570
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  851): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  851): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  851): tsOffsetIs: Apps: 215153848256; DSPS: 7141617; Offset : -2794191245
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1730): disconnect managed GoogleApiClient
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  851): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  851): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  851): tsOffsetIs: Apps: 235154602363; DSPS: 7797002; Offset : -2794200181
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/HeadsetStateMachine( 1986): Disconnected process message: 10, size: 0
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
W/Settings(  851): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  851): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  851): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  851): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  851): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  851): tsOffsetIs: Apps: 255155419491; DSPS: 8452389; Offset : -2794207054
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  851): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  851): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  851): tsOffsetIs: Apps: 275156167087; DSPS: 9107773; Offset : -2794191880
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  851): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  851): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  851): tsOffsetIs: Apps: 295156929007; DSPS: 9763158; Offset : -2794192978
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5577): --= Surplus to requirements =--
I/jxcore-log( 5577): 
I/jxcore-log( 5577): ****TEST TOOK:  ms ****
I/jxcore-log( 5577): 
I/jxcore-log( 5577): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5577): 
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/AndroidRuntime( 8053): 
D/AndroidRuntime( 8053): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8053): CheckJNI is OFF
,D/AndroidRuntime( 8053): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  851): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  851): Killing 5577:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  851): WIN DEATH: Window{1f11c2f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  851): Skipping PackageSetting{69eb557 com.example.hello/10317} due to missing metadata
D/InputDispatcher(  851): Focus left window: Window{1f11c2f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  851): Window went away: Window{1f11c2f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  851):   Force finishing activity ActivityRecord{3a8c7667 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  851): Display changed displayId=0
D/DSDPConnection( 1748): Display #0 changed.
,W/ActivityManager(  851): Spurious death for ProcessRecord{15b63101 5577:com.test.thalitest/u0a316}, curProc for 5577: null
,I/ActivityManager(  851): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/System.err( 3598): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 3598): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3598): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3598): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3598): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3598): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3598): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3598): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3598): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3598): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3598): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3598): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  851): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1730): Ignoring removeGeofence because network location is disabled.
,I/ActivityManager(  851): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8084 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1875): [Launcher.java:5203:onStart()]onStart
I/art     ( 1936): Explicit concurrent mark sweep GC freed 21460(1253KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 2.507ms total 129.376ms
,I/[LGHome]EVENT( 1875): [Launcher.java:776:onResume()]onResume
I/art     ( 5748): Explicit concurrent mark sweep GC freed 22823(1312KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 13MB/18MB, paused 936us total 136.327ms
,W/SQLiteConnectionPool( 5748): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/[LGHome]EVENT( 1875): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1875): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1875): [Launcher.java:929:onResume()]onResume end
I/Activity( 1875): Activity.onPostResume() called 
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
,W/[LGHome]LGWallpaperInfo( 1875): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1875): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1372): handleShortcutListChanged...
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
,D/WindowManager(  851): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
I/SystemUI[Framework](  851): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,I/[SystemUI]NavigationThemeResource( 1372): notify navigation bar color(0x0)
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PhoneWindowManagerEx(  851): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  851): setLGSystemUiVisibility(0x0)
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/StatusBarManagerServiceEx(  851): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/InputDispatcher(  851): Focus entered window: Window{156f934b u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/SystemUI[Framework](  851): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@12a8d99c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  851): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourcesManager( 8084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8084): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/ResourcesManager( 8084): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
,I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1875): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1372): handleShortcutListChanged...
,I/art     (  851): Explicit concurrent mark sweep GC freed 59526(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 3.093ms total 287.771ms
,I/art     (  851): WaitForGcToComplete blocked for 164.230ms for cause Explicit
I/LGEmail ( 8084): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/administrator(  851): Handling package changes for user 0
,D/LGEmail ( 8084): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
W/InputMethodManagerService(  851): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  851): Got RemoteException sending setActive(false) notification to pid 5577 uid 10316
,I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  851): Timeline: Activity_windows_visible id: ActivityRecord{9b5b5ab u0 com.lge.launcher2/.Launcher t221} time:305619
,I/art     (  851): Explicit concurrent mark sweep GC freed 7868(472KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.503ms total 320.282ms
W/IInputConnectionWrapper( 1875): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1605): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/PackageChangeReceiver( 8084): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
D/AppUp4:PreloadHelper( 7748): added Exclude : com.test.thalitest
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/NotificationService(  851): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  851): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  851): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  851): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8111 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  851): Killing 7208:com.google.android.talk/u0a61 (adj 15): empty #11
,I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 23.326ms
,D/AndroidRuntime( 8053): Shutting down VM
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 22.966ms
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.684ms
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
W/libprocessgroup(  851): failed to open /acct/uid_10061/pid_7208/cgroup.procs: No such file or directory
,D/TaskPersister(  851): removeObsoleteFile: deleting file=222_task.xml
I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager(  851): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,W/IInputConnectionWrapper( 1875): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
W/ResourceType(  851): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 8111): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8111): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8111): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8111): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8111): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SharedPreferencesImpl( 1875): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
I/Timeline( 1875): Timeline: Activity_idle id: android.os.BinderProxy@bf02943 time:306253
,I/art     ( 1875): Explicit concurrent mark sweep GC freed 31925(1721KB) AllocSpace objects, 20(2MB) LOS objects, 40% free, 15MB/25MB, paused 1.512ms total 53.740ms

```
