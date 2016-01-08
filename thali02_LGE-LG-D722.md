#### Test 549702613245198_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  972): Killing 5735:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10053/pid_5735/cgroup.procs: No such file or directory
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{a67987e type 2 when 90785 com.android.providers.calendar} when 90785
I/ActivityManager(  972): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5946 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 5946): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
--------- beginning of main
D/CalendarProvider2( 5946): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@992e425
D/CalendarProvider2( 5946): [getOrCreateCalendarAlarmManager]
D/UEI.SmartControl( 5589): Internal timer expired: 1
I/CalendarProvider2( 5946): Created com.android.providers.calendar.CalendarAlarmManager@181a5bc6(com.android.providers.calendar.CalendarProvider2@992e425)
D/CalendarProviderBroadcastReceiver( 5946): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5946): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5946): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 5946): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5946): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 5946): [IntentService] Release Lock
D/CalendarProvider2( 5946): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  972): Killing 5871:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10011/pid_5871/cgroup.procs: No such file or directory
D/AndroidRuntime( 5944): 
D/AndroidRuntime( 5944): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5944): CheckJNI is OFF
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/AndroidRuntime( 5944): Calling main entry com.android.commands.am.Am
I/ActivityManager(  972): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  972): setTaskToReturnTo : TaskRecord{29143956 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  972): setTaskToReturnTo : TaskRecord{29143956 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  972): AppWindowTokenEx init.. 
D/ContextHelper(  972): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1881): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  972): Focus left window: Window{2c525582 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5944): Shutting down VM
D/SplitWindow(  972): check instance of lgWin Window{3e2f1b30 u0 Starting com.test.thalitest}
I/ActivityManager(  972): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5985 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1881): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1881): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  972): Starting window displayed
I/HotwordDetector( 1945): Closing mic
I/SystemUI[Framework](  972): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
I/MicrophoneInputStream( 1945): mic_close com.google.android.apps.gsa.speech.audio.u@346b37ff
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  972): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  972): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  972): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3c3c3289,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioRecord( 1945): stop()
D/AudioRecord( 1945): AudioRecord->stop()
V/AudioFlinger(  277): RecordHandle::stop()
V/AudioFlinger(  277): RecordThread::stop
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1374): draw background and invalidate : color = c000000
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
D/BarTransitions( 1374): draw background and invalidate : color = b0b0b0b
V/AudioFlinger(  277): processConfigEvents_l() remaining events 1
V/AudioFlinger(  277): processConfigEvents_l() DONE thread 0xb426f000
,D/audio_hw_primary(  277): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
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
V/AudioFlinger(  277): processConfigEvents_l() DONE thread 0xb426f000
V/AudioFlinger(  277): RecordThread: loop stopping
V/AudioPolicyService(  277): AudioCommandThread() going to sleep
V/AudioRecord( 1945): stop()
V/AudioRecord( 1945): stop()
V/AudioRecord( 1945): stop()
V/AudioFlinger(  277): RecordHandle::stop()
V/AudioFlinger(  277): RecordThread::stop
V/AudioPolicyManager(  277): releaseInput() 17
V/AudioPolicyManager(  277): closeInput(17)
V/AudioFlinger(  277): closeInput() 17
V/AudioSystem(  277): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  277): ThreadBase::exit
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  277): RecordThread: loop starting
V/AudioSystem( 1756): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1945): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  277): RecordThread 0xb426f000 exiting
D/audio_hw_primary(  277): adev_close_input_stream: enter:stream_handle(0xb40367a0)
D/audio_hw_primary(  277): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
V/audio_hw_primary(  277): in_standby: exit:  status(0)
V/AudioPolicyService(  277): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  277): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  277): releaseInput() exit
V/AudioPolicyService(  277): AudioCommandThread() waking up
V/AudioPolicyService(  277): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  277): AudioCommandThread() going to sleep
V/AudioSystem(  972): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2003): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2107): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3187): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  277): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  277): removeClient_l() pid 1945, calling pid 277
V/AudioFlinger(  277): releasing 16 from 1945 for -1
V/AudioFlinger(  277):  decremented refcount to 0
V/AudioFlinger(  277): purging stale effects
I/HotwordRecognitionRnr( 1945): Stopping hotword detection.
I/HotwordRecognitionRnr( 1945): Hotword detection finished
D/ContextHelper( 5985): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5985): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5985): Time to load native libraries: 12 ms (timestamps 2147-2159)
I/LibraryLoader( 5985): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5985): Binding Chromium to main looper Looper (main, tid 1) {181a5bc6}
I/LibraryLoader( 5985): Expected native library version number "",actual native library version number ""
I/chromium( 5985): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5985): Initializing chromium process, singleProcess=true
W/art     ( 5985): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5985): ApplicationContext is null in ApplicationStatus
W/chromium( 5985): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5985): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5985): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5985): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5985): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5985): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5985): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5985): Remote Branch: 
I/Adreno-EGL( 5985): Local Patches: 
I/Adreno-EGL( 5985): Reconstruct Branch: 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/AudioPolicyService(  277): registerClient() client 0xb4027140, uid 10316
,D/BluetoothManagerService(  972): Message: 20
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1aedfa92:true
D/BluetoothAdapterService(1045458514)( 2003): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@215f9d38
W/art     ( 5985): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5985): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5985): CordovaWebView is running on device made by: LGE
,W/art     ( 5985): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5985): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5985): Activity.onPostResume() called 
,D/OpenGLRenderer( 5985): Render dirty regions requested: true
I/OpenGLRenderer( 5985): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5985): Enabling debug mode 0
,D/Atlas   ( 5985): Validating map...
,D/SplitWindow(  972): check instance of lgWin Window{ce62c42 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5985): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  972): Focus entered window: Window{ce62c42 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  972): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  972): Displayed com.test.thalitest/.MainActivity: +1s172ms
I/Timeline(  972): Timeline: Activity_windows_visible id: ActivityRecord{1598cdd7 u0 com.test.thalitest/.MainActivity t220} time:92812
I/Timeline( 5985): Timeline: Activity_idle id: android.os.BinderProxy@2de2cd4d time:92845
,W/BindingManager( 5985): Cannot call determinedVisibility() - never saw a connection for the pid: 5985
,D/AlertService( 5821): Beginning updateAlertNotification
,D/JsMessageQueue( 5985): Set native->JS mode to OnlineEventsBridgeMode
D/AlertService( 5821): No fired or scheduled alerts
I/NotificationManager( 5821): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 5821): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(16) by com.android.calendar
,I/NotificationManager( 5821): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5821): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5821): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 5821): No events found starting within 1 week.
,I/ActivityManager(  972): Killing 5821:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10013/pid_5821/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/jxcore_app_log( 5985): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622858240
D/JX-Cordova( 5985): jxcore cordova android initializing
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{2a16cacb type 0 when 1452283664772 com.android.vending} when 1452283664772
D/Finsky  ( 5475): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  972): android: cancelAsUser(2) by android
,D/libc-netbsd( 5475): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5475): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5475): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5475): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 5475): propertyValue:false
D/libc-netbsd( 5475): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5475): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     ( 5985): CheckpointMarkThreadRoots callback created = 0x9f55f4b0
,I/art     ( 5985): CheckpointMarkThreadRoots callback created = 0x9f55f480
,D/libc-netbsd( 5475): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5475): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  972): android: cancelAsUser(2) by android
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/qtaguid ( 5475): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5475): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5475): untagSocket(41) failed with errno -22
D/Finsky  ( 5475): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  972): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6069 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  972): android: cancelAsUser(2) by android
,I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 25.873ms
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 326us total 25.347ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 330us total 21.236ms
,W/ResourcesManager( 6069): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6069): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 94690090593; DSPS: 3193847; Offset : -2782649383
,I/qtaguid ( 5475): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5475): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5475): untagSocket(41) failed with errno -22
I/MultiDex( 6069): VM with version 2.1.0 has multidex support
I/MultiDex( 6069): install
I/MultiDex( 6069): VM has multidex support, MultiDex support library is disabled.
,I/art     (  972): Explicit concurrent mark sweep GC freed 28842(1426KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.041ms total 241.670ms
V/JNIHelp ( 6069): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6069): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6069): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15b21798: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6069): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6069): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6069): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1737): callingUid 10006, callindPid: 1737
E/MDM     ( 1737): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1737): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4149): Restart initialization of location
V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 6069): Reading stored module config
I/NotificationManager( 1737): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1737): No location to return for getLastLocation()
,D/ChimeraCfgMgr( 6069): Loading module com.google.android.gms.car from APK com.google.android.gms
W/FusedLocationProvider( 1737): location=null
I/art     ( 5475): CheckpointMarkThreadRoots callback created = 0xb057d930
,I/art     ( 5475): CheckpointMarkThreadRoots callback created = 0xb057d900
,D/CAR.SERVICE( 6069): Connecting to CarCallService...
,D/NativeLibraryUtils( 6069): Install completed successfully. count=14 extracted=0
I/art     ( 6069): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6069): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6069): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6069): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6069): Creating a new PhoneAdapter instance
W/ActivityManager(  972): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6069): setListener: com.google.android.gms.car.dn@28afa347
W/ActivityManager(  972): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6069): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6069): Starting CarCallService with initial phone null
,I/NotificationManager( 6069): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6069): Package validated; name: com.android.vending
,I/ActivityManager(  972): Process com.google.android.talk (pid 5545) has died
,I/NotificationManager( 5475): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5475): [1] GearheadStateMonitor.access$100: mIsProjecting:false
W/jxcore-log( 5985): Initializing JXcore engine
,W/jxcore-log( 5985): JXcore engine is ready
W/jxcore-log( 5985): Starting JXcore engine
,W/.test.thalitest( 5985): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5560]" dev="sockfs" ino=5560 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 5985): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5985): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8233]" dev="sockfs" ino=8233 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5985): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5985): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5985): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26265]" dev="sockfs" ino=26265 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
E/lowmemorykiller(  244): Error writing /proc/5676/oom_score_adj; errno=22
V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  972): Process com.android.contacts (pid 5676) has died
,I/NotificationManager(  972): android: cancelAsUser(2) by android
,W/jxcore-log( 5985): Platform android
W/jxcore-log( 5985): 
,W/jxcore-log( 5985): Process ARCH arm
W/jxcore-log( 5985): 
,I/qtaguid ( 5475): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5475): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5475): untagSocket(41) failed with errno -22
,W/ResourcesManager( 5475): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5475): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 5475): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5475): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{192ed85a type 0 when 1452283667576 com.android.vending} when 1452283667576
,D/Finsky  ( 5475): [670] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1737): client connected with version: 8296000
V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  972): android: cancelAsUser(2) by android
,D/Finsky  ( 5475): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5475): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 5475): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5475): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5475): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5475): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 5475): propertyValue:false
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{3e354b80 type 0 when 1452283667977 com.google.android.googlequicksearchbox} when 1452283667977
,I/jxcore-log( 5985): JXcore Cordova bridge is ready!
I/jxcore-log( 5985): 
W/jxcore-log( 5985): JXcore engine is started
,I/chromium( 5985): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 5985): Skipped 208 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 5985): Toggling radios to true
I/jxcore-log( 5985): 
,D/BluetoothAdapter( 5985): enable(): BT is already enabled..!
D/WifiServiceImplEx(  972): setWifiEnabled: true pid=5985, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  972): setWifiEnabled: true pid=5985, uid=10316
D/WifiServiceImplEx(  972): disconnect pid=5985, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  972): reconnect pid=5985, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5985): Radios toggled
I/jxcore-log( 5985): 
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2715): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2715): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  972): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1808): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService(  972): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  972): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  972): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  273): Clearing all IP addresses on wlan0
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 7
,V/NativeCrypto( 1737): Read error: ssl=0xaaf50e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1737): SSL shutdown failed: ssl=0xaaf50e00: I/O error during system call, Broken pipe
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 7
,D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  972): ignoring duplicate network state non-change
D/WifiHS20(  972): hidePasspointNotification off =false
,W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:48.538 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/ActivityManager(  972): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6132 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/WifiStateMachine(  972): Start Disconnecting Watchdog 1
D/WifiHS20(  972): hidePasspointNotification off =false
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  972): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  972): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2715): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  273): Clearing all IP addresses on wlan0
,D/ConnectivityService(  972): Default network via Wi-Fi disconnect. stop DSQN
D/WifiHS20(  972): hidePasspointNotification off =false
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DSQN    (  972): disableDataServiceNotify
D/DSQN    (  972): stop dsqn bin
D/ConnectivityService(  972): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:48.657 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:48.658 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  972): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524292
D/Nat464Xlat(  972): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker(  972): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  972): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): ValidatedState{ when=-4ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=-14ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): Forcing reevaluation
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  972): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  972): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  972): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  972): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  972): Removing idletimer
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
W/QCNEJ   ( 1833): |CORE| No family connected
W/QCNEJ   ( 1833): |CORE| No family connected
I/QCNEJ   ( 1833): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/DhcpStateMachine(  972): StoppedState
D/DhcpStateMachine(  972): StoppedState{ when=-63ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServiceExtension( 1808): isInternetCheckAvailable return false
D/Tethering(  972): MasterInitialState.processMessage what=3
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): ValidatedState{ when=-21ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  972): MasterInitialState.processMessage what=3
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=-21ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
V/NetworkPolicy(  972): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  972): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): Disconnected - quitting
I/QCNEJ   ( 1833): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1756): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1756):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/Settings(  972): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/WifiServiceExtension( 1808): isInternetCheckAvailable return false
D/WifiNetworkAgent(  972): NetworkAgent: NetworkAgent channel lost
D/WifiHS20(  972): hidePasspointNotification off =false
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WIFI    (  972): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  972):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:48.718 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:48.719 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateDISCONNECTED
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateSCANNING
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
W/ResourcesManager( 6132): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6132): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6132): Asset path '/system/framework/com.lge.mdm.jar' does not exist or, contains no resources.
,W/ResourcesManager( 6132): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6132): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6132): Using schema version: 115
,I/IndexDatabaseHelper( 6132): Index is fine
I/ActivityManager(  972): Process com.google.android.apps.plus (pid 5423) has died
,V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{1eb255b9 type 2 when 98088 com.google.android.gms} when 98088
,D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
I/ActivityManager(  972): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6164 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6164): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6164): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6164): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
I/PCSuite ( 6164): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6164): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6164): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
I/PCSuite ( 6164): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6164): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6164): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6186 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6186): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2715): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:49.788 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,D/LocSvc_java(  972): onReceive
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/wpa_supplicant( 2715): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:49.809 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:49.831 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:49.832 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2715): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2715): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateGROUP_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/WifiServiceExtension(  972): setVHTCapabilityType  : false
I/Babel_SMS( 6186): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6186): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6186): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6186): MmsConfig.loadFromDatabase
I/WifiServerServiceExt(  972): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt(  972): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  972): setSecurityType  : 2
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:49.913 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:49.915 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/ConnectivityService(  972): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  972): Got NetworkAgent Messenger
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  972): NetworkAgent connected
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1808): isInternetCheckAvailable return false
,E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/Babel_SMS( 6186): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6186): MmsConfig.loadFromResources
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
E/Babel_SMS( 6186): canonicalizeMccMnc: invalid mccmnc nullnull
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/Babel_SMS( 6186): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  273): Setting iface cfg
,E/WifiStateMachine(  972): Start Dhcp Watchdog 2
D/DhcpStateMachine(  972): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  972): WaitBeforeStartState
I/QCNEJ   ( 1833): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-55 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:49.952 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  972): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/SensorManager( 6186): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6186): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6186): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 6186): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6186): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6186): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6186): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6186): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6186): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6186): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6186): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6186): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6186): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6186): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6186): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6186): found sensor: Motion Accel, handle=46
E/WifiStateMachine(  972): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  972): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  972): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@151efc50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  972): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@151efc50 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  972): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  972): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  972): DHCP Start wake lock is acquired.
D/CommandListener(  273): Setting iface cfg
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  273): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper(  972): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateCOMPLETED
D/ConnectivityService(  972): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  972): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  972): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  972): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  972): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService(  972): ignoring duplicate network state non-change
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1808): isInternetCheckAvailable return false
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:50.072 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  972): Adding iface wlan0 to network 101
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1808): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:50.081 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 3
I/art     ( 6186): CheckpointMarkThreadRoots callback created = 0xaaf4a8d0
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:50.097 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
E/WifiStateMachine(  972): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20(  972): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
W/Settings( 6186): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiHS20(  972): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
E/ConnectivityService(  972): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  972): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService(  972): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:50.12 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  273): netlink response contains error (File exists)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/ConnectivityService(  972): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  972): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  972): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  972): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  972): requiresClat: netType=1, connected=true, has,IPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  972): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=-13ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): Connected
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 3
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  972): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  972):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  972):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  972): currentScore = 0, newScore = 20
D/ConnectivityService(  972):    accepting network in place of null
D/ConnectivityService(  972): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1756): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  972): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  972):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1756):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  972): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  972): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=f,alse mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): [LWD] wait 500ms before dns check
D/ConnectivityService(  972): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  972): [e] list.add(nai) empty : false size: 1
I/Babel_Crash( 6186): startup - clean
D/ConnectivityService(  972): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  972): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1833): |CORE| No family connected
I/QCNEJ   ( 1833): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1833): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  972): validation of new default Network = false
D/ConnectivityService(  972): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  972): enableDataServiceNotify 
D/DSQN    (  972): start dsqn bin
V/NetworkPolicy(  972): [LG_RESTRICTED] checkMobilePolicy_type()
I/art     ( 6186): CheckpointMarkThreadRoots callback created = 0xaaf4a8b0
,D/ConnectivityService(  972): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/DSQN    ( 6223): DSQN samuel.seo ver 141203
E/DSQN    ( 6223): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6223): created command queue thread
I/DSQN    ( 6223): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6223): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/Babel   ( 6186): deleted: false for 0
,V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
D/DhcpStateMachine(  972): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  972): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  972): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/AudioCapabilities( 6186): Unsupported mime audio/x-lg-flac
I/PCSuite ( 6164): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6164): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6164): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/AudioCapabilities( 6186): Unsupported mime audio/adpcm
I/dhcpcd  ( 6226): version 5.5.6 starting
E/dhcpcd  ( 6226): get_duid: Read-only file system
V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6186): Unsupported mime audio/g726
,D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
W/AudioCapabilities( 6186): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6186): Unsupported mime audio/wma-voice
V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/libc-netbsd( 1737): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1737): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1737): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1737): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
,W/VideoCapabilities( 6186): Unsupported mime video/mjpg
D/WiFiOffLoadBroadcast( 6132): Not supported operator for automatic switch
,V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
W/VideoCapabilities( 6186): Unsupported mime video/theora
,V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/dhcpcd  ( 6226): wlan0: rebinding lease of 192.168.1.134
D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
,D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 1737): propertyValue:false
V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
W/AudioCapabilities( 6186): Unsupported mime audio/evrc
W/AudioCapabilities( 6186): Unsupported mime audio/qcelp
W/VideoCapabilities( 6186): Unrecognized profile 2130706433 for video/avc
,I/DSQN    ( 6223): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6223): restart monitoring
D/LGDataListener(  273): argv[0]=dsqncommand
D/LGDataListener(  273): argv[1]=wlan0
D/LGDataListener(  273): argv[2]=1
D/LGDataListener(  273): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6223): dsqn report finish
D/DSQN    (  972): DSQM DsqnNotification wlan0  1
D/DSQN    (  972): start to monitor internet connection
W/AudioCapabilities( 6186): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6186): Unsupported mime audio/qcelp
W/AudioCapabilities( 6186): Unsupported mime audio/evrc
,D/libc-netbsd( 1737): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1737): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6186): Unsupported mime video/mp4v-esdp
D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
D/libc-netbsd( 1737): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1737): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/VideoCapabilities( 6186): Unsupported profile 4 for video/mp4v-es
,V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
,W/VideoCapabilities( 6186): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6186): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6186): Unrecognized profile 2130706433 for video/avc
,D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
I/PCSuite ( 6164): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6164): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,W/VideoCapabilities( 6186): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6132): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6132): MCCMNC not supported: null
,I/PCSuite ( 6164): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
I/vclib   ( 6186): onServiceConnected
D/PCSuite ( 6164): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
W/Babel   ( 6186): Attempted to change video mute state without an active call.
I/ActivityManager(  972): Killing 5893:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/NotificationManager( 6186): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): [LWD] DNSResolver start dns
,D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
W/libprocessgroup(  972): failed to open /acct/uid_10023/pid_5893/cgroup.procs: No such file or directory
,D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out(  972): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 20:07:50 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452283670750], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452283670720]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1808): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): Validated
D/ConnectivityService(  972): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  972):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  972): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  972): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  972): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiDataContinuityService(  972): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/WIFI    (  972):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1756): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1756):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  972): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/ActivityManager(  972): Killing 5698:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  972): failed to open /acct/uid_10069/pid_5698/cgroup.procs: No such file or directory
D/ConnectivityService(  972): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  972): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  972): identical MTU - not setting
D/Nat464Xlat(  972): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  972): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  972): enableDataServiceNotify 
D/DSQN    (  972): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524295
I/dhcpcd  ( 6226): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
I/QCNEJ   ( 1833): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:51.618 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/dhcpcd  ( 6226): wlan0: leased 192.168.1.134 for 86400 seconds
,D/DSQN    (  972): dsqn is running restart
I/DSQN    ( 6251): DSQN samuel.seo ver 141203
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
E/DSQN    ( 6251): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6251): created command queue thread
I/DSQN    ( 6251): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6251): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  972): onReceive
D/LocSvc_java(  972): got connectivity action
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  972): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  972): broadcast - no network connections
D/LocSvc_java(  972): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  972): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  972): onReceive
D/LocSvc_java(  972): got connectivity action
D/LocSvc_java(  972): broadcast - no network connections
D/LocSvc_java(  972): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  972): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  972): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  972): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  972): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  972): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  972): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  972): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  972): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6262 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider(  972): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  972): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  972): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  972): Process com.android.vending (pid 5475) has died
,D/CAR.SERVICE( 6069): mConnectedToCar = false, abort
,E/ActivityThread( 6069): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1817d94f that was originally bound here
E/ActivityThread( 6069): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1817d94f that was originally bound here
E/ActivityThread( 6069): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6069): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6069): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6069): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6069): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6069): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6069): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6069): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6069): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6069): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6069): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6069): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6069): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6069): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6069): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6069): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6069): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6069): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6069): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6069): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6069): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6069): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6069): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6069): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@4f43e86 that was originally bound here
E/ActivityThread( 6069): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@4f43e86 that was originally bound here
E/ActivityThread( 6069): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6069): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6069): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6069): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6069): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6069): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6069): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6069): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6069): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6069): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6069): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6069): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6069): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6069): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6069): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6069): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6069): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6069): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6069): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6069): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6069): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6069): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  972): Unbind failed: could not find connection for android.os.BinderProxy@123aabe3
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  972): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  972): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  972): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  972): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  972): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  972): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  972): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  972): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  972): RunningState
I/MusicStore( 6262): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6262): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6262): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6262): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6262): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6262): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6262): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6262): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6262): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31bf14d3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6262): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6262): GMSCore installation verified
I/ConfigStore( 6262): Config Database version: 1
,I/MediaRouter( 6262): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6262): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6262): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6262): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  972): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6313 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6262): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6262): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 6262): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6313): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6313): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/QCNEJ   ( 1833): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 21:07:52.97 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/LGEmail ( 6313): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6313): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,V/WifiInternetCheck(  972): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/NotificationManager( 1945): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  972): onReceive
D/LocSvc_java(  972): got connectivity action
,D/LocSvc_java(  972): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  972): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  972): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  972): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  972): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 6262): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider(  972): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  972): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1808): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1808): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
D/WifiController(  972): battery changed pluggedType: 2
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,D/charger_monitor(  492): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
,D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/eas_req ( 6313): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  972): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6348 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 6313): JNI_OnLoad()
I/HubEmail( 6313): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6313): registerNatives()
I/HubEmail( 6313): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6313): registerNativeMethods()
I/HubEmail( 6313): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6313): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6313): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  972): Killing 5946:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10014/pid_5946/cgroup.procs: No such file or directory
,D/LGDMClient( 6348): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6348): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6348): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6348): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6348): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6348): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6348): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6348): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6375 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6348): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6348): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6348): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6348): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6348): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6348): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  972): Killing 6069:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6375): onCreate
,W/libprocessgroup(  972): failed to open /acct/uid_10006/pid_6069/cgroup.procs: No such file or directory
W/AppUp4:DB( 6375):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6375):  setFingerPrint start
,I/AppUp4:DB( 6375):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6375):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6375):  SDK version = 0
I/AppUp4:DB( 6375):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6375): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6375): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6375): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6375): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6375): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6375): onReceive
I/AppUp4:CustModeStarterReceiver( 6375): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6375): Context : android.app.ReceiverRestrictedContext@c539787
D/AppUp4:CustFacade( 6375): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6375): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6375): begin check event
I/AppUp4:CustModeStarterReceiver( 6375): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6375): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6375): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6375): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6375): handleAsyncCustNotification do not startCustService
I/ActivityManager(  972): Killing 6132:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_6132/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3187): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3187): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3187): networkInfo.isConnected() = false
I/ActivityManager(  972): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6397 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out(  972): propertyValue:false
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out(  972): propertyValue:false
I/DSQN    ( 6251): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6251): restart monitoring
,I/DSQN    ( 6251): dsqn report finish
D/LGDataListener(  273): argv[0]=dsqncommand
D/LGDataListener(  273): argv[1]=wlan0
D/LGDataListener(  273): argv[2]=1
D/LGDataListener(  273): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  972): DSQM DsqnNotification wlan0  1
D/DSQN    (  972): start to monitor internet connection
V/WifiInternetCheck(  972): isHttpConnectionAvailable - We got a valid response : 204
,D/PhoneMonitor( 6397): Register our PhoneStateListener
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
D/MobileConnectivityChangeReceiver( 6397): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6397): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  972): Killing 5589:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5003): android.os.DeadObjectException
,W/System.err( 5003): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5003): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5003): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5003): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5003): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5003): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5003): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5003): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5003): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5003): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5003): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5003): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5003): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5003): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5003): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5003): android.os.DeadObjectException
W/System.err( 5003): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5003): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5003): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5003): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5003): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5003): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5003): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5003): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5003): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5003): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5003): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5003): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5003): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5003): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5003): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  270): 
I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/libprocessgroup(  972): failed to open /acct/uid_10089/pid_5589/cgroup.procs: No such file or directory
,W/ActivityManager(  972): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
V/DownloadManager( 3204): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneMonitor( 6397): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6397): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6397): [parse] Load xml
V/TelephonyAutoProfiling( 6397): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6397): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,I/ActivityManager(  972): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6427 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/DownloadManager( 3204): DownloadService onCreate
,D/PhoneMonitor( 6397): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/DownloadManager( 3204): in removeSpuriousFiles
I/NotificationManager( 3204): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/ActivityManager(  972): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6451 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@15b21798 on behalf of 3204
,I/DownloadManager( 3204): in trimDatabase
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@17948bf1 on behalf of 3204
V/DownloadManager( 3204): DownloadService onStartCommand
,V/DownloadManager( 3204): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@3e7d1544 on behalf of 3204
,D/UEI.SmartControl( 6427): Quickset Services start...
,I/UEI.SmartControl( 6427): Manufacture = LGE
I/art     (  972): Explicit concurrent mark sweep GC freed 85901(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.376ms total 234.806ms
D/UEI.SmartControl( 6427): File observer start...
E/UEI.SmartControl( 6427): IR Port is disabled: false
D/UEI.SmartControl( 6427): Starting file observer...
D/UEI.SmartControl( 6427): Extracting JNI libs...
D/UEI.SmartControl( 6427): --- this system supports 32-bit or 64-bit only
I/CheckinService( 4149): Checkin interval check for package: unspecified last checkin: 1452283649596 min interval config: 0 actual interval: 25455
I/CheckinService( 4149): Checking schedule, now: 1452283675061 next: 1452283679554
I/CheckinService( 4149): active receiver: disabled
,V/DownloadManager( 3204): DownloadService onDestroy
I/ActivityManager(  972): Killing 6164:com.lge.sync/1000 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 6427): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6427): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6427): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6427): --- Selecting new region: 2
,I/UEI.SmartControl( 6427): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6427): Platform has CIR...
D/UEI.SmartControl( 6427): NO CIR support, need to check package...
I/UEI.SmartControl( 6427): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6427): QS Service created
,W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_6164/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2754): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:7:55
D/UpdateThreadPoolManager( 2754): 2 : This is isUpdating : false
D/WeatherAncestor( 2754): connectivity changed - connection : true
D/Weather_cast( 2754): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2754): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:7:55
D/WeatherService( 2754): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
E/UEI.SmartControl( 6427): QS start get config
,I/ActivityManager(  972): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6472 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  972): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2754): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 424us total 20.914ms
,D/UEI.SmartControl( 6427): Loading JNI Libs...
D/UEI.SmartControl( 6427):  configuring local db...
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 20.512ms
,D/WeatherService( 2754): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2754): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.126ms
,D/libc-netbsd( 6186): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6186): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6186): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6186): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  273): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 6186): propertyValue:false
I/Babel   ( 6186): connection state changed from UNKNOWN to CONNECTED
,D/UEI.SmartControl( 6427):  ---- Has DB8: true
,D/UEI.SmartControl( 6427): QS start statue = true Error code = 0
D/UEI.SmartControl( 6427): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 6427): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
D/UEI.SmartControl( 6427): IRRCDataComm has AudioManager!!!!.
W/ContextImpl( 6472): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6472): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/irrc_jni( 6427): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6427): IrrcClient ++ 
D/irrcClient( 6427): getIrrcService ++ 
D/irrcClient( 6427): getIrrcService -- 
D/irrcClient( 6427): IrrcClient -- 
W/irrc_jni( 6427): IRRCPlayer_nativeInit -- 
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6472): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/UEI.SmartControl( 6427): Services init done
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6472): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/UEI.SmartControl( 6427): Device manager: loading config....
D/UEI.SmartControl( 6427): QS Service init finished
D/UEI.SmartControl( 6427): QS Service version name: 0.1.73
D/UEI.SmartControl( 6427): QS Service version code: 1073
D/UEI.SmartControl( 6427): Service requested: Control
D/UEI.SmartControl( 6427): Config is loaded...
,I/ActivityManager(  972): Killing 5003:com.lge.qremote/u0a106 (adj 15): empty #11
I/GAv4    ( 6472): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6472):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6472):   adb logcat -s GAv4
D/UEI.SmartControl( 6427):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6427): Notify AllClients services are ready: 0
,W/libprocessgroup(  972): failed to open /acct/uid_10106/pid_5003/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6427): Internal service binding...
,W/GAv4    ( 6472): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6472): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6472): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/SQLiteConnectionPool( 4149): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/WebViewFactory( 6472): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6472): Time to load native libraries: 2 ms (timestamps 5364-5366)
I/LibraryLoader( 6472): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6472): Binding Chromium to main looper Looper (main, tid 1) {302696c8}
I/LibraryLoader( 6472): Expected native library version number "",actual native library version number ""
I/chromium( 6472): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6472): Initializing chromium process, singleProcess=true
,W/art     ( 6472): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6472): ApplicationContext is null in ApplicationStatus
W/chromium( 6472): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6472): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6472): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6472): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6472): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6472): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6472): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6472): Remote Branch: 
I/Adreno-EGL( 6472): Local Patches: 
I/Adreno-EGL( 6472): Reconstruct Branch: 
V/AudioPolicyService(  277): registerClient() client 0xb42bb620, uid 10079
,W/AudioManagerAndroid( 6472): Requires BLUETOOTH permission
I/NSApplication( 6472): Starting up...
,I/ActivityManager(  972): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6546 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 6262:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10081/pid_6262/cgroup.procs: No such file or directory
,I/ActivityManager(  972): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6565 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 6313:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10021/pid_6313/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6565): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  972): Killing 6348:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_6348/cgroup.procs: No such file or directory
,I/ActivityManager(  972): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6589 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6589): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6589): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
V/AlarmManager(  972): RTC_WAKEUP set : Alarm{2a2e5951 type 0 when 1452283678160 com.google.android.googlequicksearchbox} when 1452283678160
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6589): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6589): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6589): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6589): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6589): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6589): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31bf14d3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6589): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6589): GMSCore installation verified
I/ConfigStore( 6589): Config Database version: 1
,I/MediaRouter( 6589): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6589): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6589): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6589): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  972): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6630 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  972): Process com.uei.lg.quicksetsdk.lite (pid 6427) has died
,I/GHttpClientFactory( 6589): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6589): Using platform SSLCertificateSocketFactory
I/NotificationManager( 6589): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6630): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6630): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6630): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 6630): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6630): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  972): Process com.google.android.talk (pid 6186) has died
,D/eas_req ( 6630): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  972): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6668 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6630): JNI_OnLoad()
I/HubEmail( 6630): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6630): registerNatives()
I/HubEmail( 6630): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6630): registerNativeMethods()
I/HubEmail( 6630): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6630): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6630): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/LGDMClient( 6668): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6668): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6668): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6668): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 6375): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6375): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6375): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6375): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6375): onReceive
I/AppUp4:CustModeStarterReceiver( 6375): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6375): Context : android.app.ReceiverRestrictedContext@c539787
D/AppUp4:CustFacade( 6375): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6375): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6375): begin check event
I/AppUp4:CustModeStarterReceiver( 6375): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/LgeMiscReceiver( 3187): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3187): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3187): networkInfo.isConnected() = false
D/LGDMClient( 6668): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 6397): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6397): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 6668): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3204): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3204): DownloadService onCreate
D/WeatherAncestor( 2754): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:7:59
D/LGDMClient( 6668): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6668): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/UpdateThreadPoolManager( 2754): 2 : This is isUpdating : false
D/WeatherAncestor( 2754): connectivity changed - connection : true
D/Weather_cast( 2754): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2754): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:7:59
D/WeatherService( 2754): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 3204): in removeSpuriousFiles
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3204): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@30fcb762 on behalf of 3204
I/DownloadManager( 3204): in trimDatabase
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@134620f3 on behalf of 3204
,I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6699 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  972): getTasks: caller 10074 does not hold GET_TASKS; limiting output
W/ContextImpl( 6668): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
D/Weather.Utils( 2754): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3204): DownloadService onStartCommand
V/DownloadManager( 3204): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/WeatherService( 2754): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2754): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@1e72e7ae on behalf of 3204
E/LGDMClient( 6668): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6668): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6668): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6668): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6668): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
V/DownloadManager( 3204): DownloadService onDestroy
,I/ActivityManager(  972): Killing 6472:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/ResourcesManager( 6699): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/libprocessgroup(  972): failed to kill 1 processes for processgroup 6472
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,D/PowerManagerServiceEx(  972): acquireWakeLockInternal: lock=672932664, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=972
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
,I/[SystemUI]DateView( 1374): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/WeatherService( 2754): 2 : TimeTick Intent has been received, Time(hour:min:sec) 21:8:0
,D/WeatherService( 2754): 2 : TimeTick Intent And Screen On
D/WeatherService( 2754): 2 : SDK version : 21
W/ActivityManager(  972): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2754): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2754): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2754): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2754): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2754): 2 : This is isUpdating : false
D/WeatherService( 2754): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2754): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2754): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2754): 2 : Fixed theme : optimus
D/WeatherReflect( 2754): 2 : Map key string is -2
,D/lim     ( 2754): 2 : time = 21:08
I/Babel_SMS( 6699): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6699): MmsConfig.loadMmsSettings
I/WeatherReflect( 2754): Model Name : LG-D722
D/WeatherTheme( 2754): 2 : Different view - status_min_formatted : 07 != 08
D/WeatherTheme( 2754): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2754): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,I/Babel_SMS( 6699): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6699): MmsConfig.loadFromDatabase
D/Theme   ( 2754): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2754): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2754): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2754): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2754): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2754): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2754): forecast size is 0
,D/Theme   ( 2754): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2754): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2754): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2754): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2754): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2754): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2754): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2754): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2754): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2754): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2754): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2754): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2754): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2754): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2754): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2754): url is : null
D/Theme   ( 2754): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2754): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2754): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2754): 2 : update view, appWidgetId: 2
E/Babel_SMS( 6699): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6699): MmsConfig.loadFromResources
D/WeatherService( 2754): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 21:8:0
E/Babel_SMS( 6699): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6699): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/PowerManagerServiceEx(  972): releaseWakeLockInternal: lock=672932664 [*alarm*], flags=0x0
,D/SensorManager( 6699): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6699): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6699): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6699): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6699): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6699): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6699): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6699): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6699): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6699): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6699): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6699): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6699): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6699): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6699): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6699): found sensor: Motion Accel, handle=46
,W/Settings( 6699): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 6699): CheckpointMarkThreadRoots callback created = 0xaaf595a0
I/Babel_Crash( 6699): startup - clean
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/art     ( 6699): CheckpointMarkThreadRoots callback created = 0xaaf59580
,I/Babel   ( 6699): deleted: false for 0
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ActivityManager(  972): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6739 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6699): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6699): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6699): Unsupported mime audio/g726
W/AudioCapabilities( 6699): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6699): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6699): Unsupported mime video/mjpg
W/VideoCapabilities( 6699): Unsupported mime video/theora
,W/AudioCapabilities( 6699): Unsupported mime audio/evrc
W/AudioCapabilities( 6699): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6699): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6699): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6699): Unsupported mime audio/qcelp
W/AudioCapabilities( 6699): Unsupported mime audio/evrc
W/VideoCapabilities( 6699): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6699): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6699): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6699): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6699): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6699): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6699): onServiceConnected
W/Babel   ( 6699): Attempted to change video mute state without an active call.
,I/NotificationManager( 6699): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6699): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6699): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6699): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6699): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  273): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 6699): propertyValue:false
I/Babel   ( 6699): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  972): Killing 6546:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10048/pid_6546/cgroup.procs: No such file or directory
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6739): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6739): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6739): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6739):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6739):   adb logcat -s GAv4
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6739): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6739): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6739): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6739): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6739): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/lowmemorykiller(  244): Error writing /proc/4149/oom_score_adj; errno=22
,E/JavaBinder(  972): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  972): Scheduling restart of crashed service com.google.android.gms/.ads.identifier.service.AdvertisingIdService in 1000ms
,I/WebViewFactory( 6739): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  972): Process com.google.android.gms (pid 4149) has died
,I/LibraryLoader( 6739): Time to load native libraries: 2 ms (timestamps 299-301)
,I/LibraryLoader( 6739): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6739): Binding Chromium to main looper Looper (main, tid 1) {302696c8}
I/LibraryLoader( 6739): Expected native library version number "",actual native library version number ""
I/chromium( 6739): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6739): Initializing chromium process, singleProcess=true
,W/art     ( 6739): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6739): ApplicationContext is null in ApplicationStatus
W/chromium( 6739): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6739): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6739): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6739): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6739): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6739): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6739): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6739): Remote Branch: 
I/Adreno-EGL( 6739): Local Patches: 
I/Adreno-EGL( 6739): Reconstruct Branch: 
,V/AudioPolicyService(  277): registerClient() client 0xb42bb660, uid 10079
,W/AudioManagerAndroid( 6739): Requires BLUETOOTH permission
I/jxcore-log( 5985): Test app app.js loaded
I/jxcore-log( 5985): 
,I/art     (  972): Explicit concurrent mark sweep GC freed 20161(1029KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.252ms total 156.856ms
,I/chromium( 5985): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/NSApplication( 6739): Starting up...
I/ActivityManager(  972): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6811 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{2b8b9cc8 type 0 when 1452283679554 com.google.android.gms} when 1452283679554
,I/ActivityManager(  972): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6829 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  972): RTC_WAKEUP set : Alarm{1ee6e161 type 0 when 1452283681843 com.android.vending} when 1452283681843
,I/ActivityManager(  972): Start proc com.google.android.gms for broadcast com.google.android.gms/.mdm.receivers.ConnectivityReceiver: pid=6847 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 6589:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10081/pid_6589/cgroup.procs: No such file or directory
,W/ResourcesManager( 6847): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  972): Process com.lge.email (pid 6630) has died
,I/MultiDex( 6847): VM with version 2.1.0 has multidex support
I/MultiDex( 6847): install
I/MultiDex( 6847): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6829): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,V/JNIHelp ( 6847): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Finsky  ( 6829): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 6829): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6829): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 6829): com.android.vending: cancel(-1050172287) by com.android.vending
,W/ActivityThread( 6847): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6847): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6be985e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6847): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6847): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6847): com.google.android.gms: cancel(39789) by com.google.android.gms
D/Finsky  ( 6829): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6829): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6829): Skipping gmscore version check
,V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@2877c8dc on behalf of 6829
D/Finsky  ( 6829): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6829): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/art     ( 6847): CheckpointMarkThreadRoots callback created = 0xaaf85580
,D/NativeLibraryUtils( 6847): Install completed successfully. count=14 extracted=0
I/art     ( 6847): CheckpointMarkThreadRoots callback created = 0xaaf85570
,I/iu.SyncManager( 6847): SYNC; picasa accounts
D/Finsky  ( 6829): [835] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6829): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/NetworkLogImpl( 6847): Loaded NetworkSpeedPredictor
I/iu.Environment( 6847): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager(  972): Killing 6375:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/iu.UploadsManager( 6847): num queued entries: 0
I/iu.UploadsManager( 6847): num updated entries: 0
I/iu.SyncManager( 6847): NEXT; no task
W/libprocessgroup(  972): failed to open /acct/uid_10011/pid_6375/cgroup.procs: No such file or directory
,I/ActivityManager(  972): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6918 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 23.993ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 325us total 22.439ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.752ms
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ProcessCpuTracker(  972): Skipping unknown process pid 6894
,W/ProcessCpuTracker(  972): Skipping unknown process pid 6897
I/MusicStore( 6918): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6918): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6918): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6918): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6918): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6918): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6918): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6918): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6918): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31bf14d3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6918): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6918): GMSCore installation verified
I/ConfigStore( 6918): Config Database version: 1
,I/MediaRouter( 6918): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6918): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6918): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6918): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  972): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6952 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6918): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6918): Using platform SSLCertificateSocketFactory
I/ActivityManager(  972): Killing 6397:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10038/pid_6397/cgroup.procs: No such file or directory
,I/NotificationManager( 6918): com.google.android.music: cancel(1061) by com.google.android.music
W/ResourcesManager( 6952): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6952): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6952): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 6952): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6952): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/eas_req ( 6952): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 6668): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6668): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6668): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6668): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6668): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6668): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMClient( 6668): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6668): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6994 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6668): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6668): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6668): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6668): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6668): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6668): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/HubEmail( 6952): JNI_OnLoad()
I/HubEmail( 6952): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6952): registerNatives()
I/HubEmail( 6952): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6952): registerNativeMethods()
I/HubEmail( 6952): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6952): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  972): Killing 6451:com.lge.drmservice/u0a51 (adj 15): empty #11
W/Settings( 6952): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup(  972): failed to open /acct/uid_10051/pid_6451/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6994): onCreate
,W/AppUp4:DB( 6994):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6994):  setFingerPrint start
I/AppUp4:DB( 6994):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6994):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6994):  SDK version = 0
I/AppUp4:DB( 6994):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6994): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6994): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6994): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6994): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6994): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6994): onReceive
I/AppUp4:CustModeStarterReceiver( 6994): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6994): Context : android.app.ReceiverRestrictedContext@c539787
,D/AppUp4:CustFacade( 6994): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6994): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6994): begin check event
I/AppUp4:CustModeStarterReceiver( 6994): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6994): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6994): call method handleAsyncCustNotification.
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
D/AppUp4:CustModeStarterReceiver( 6994): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6994): handleAsyncCustNotification do not startCustService
I/ActivityManager(  972): Killing 6699:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10061/pid_6699/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3187): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3187): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3187): networkInfo.isConnected() = true
D/PhoneState( 3187): setPdpRejectCasuse : false
,I/ActivityManager(  972): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7020 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7020): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7020): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7020): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  972): Killing 6739:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10079/pid_6739/cgroup.procs: No such file or directory
,V/DownloadManager( 3204): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3204): DownloadService onCreate
,I/ActivityManager(  972): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7047 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/DownloadManager( 3204): in removeSpuriousFiles
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3204): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@305bbde5 on behalf of 3204
,I/DownloadManager( 3204): in trimDatabase
I/CheckinService( 6847): Checkin interval check for package: unspecified last checkin: 1452283649596 min interval config: 0 actual interval: 35418
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@ea2bb6b on behalf of 3204
V/DownloadManager( 3204): DownloadService onStartCommand
V/DownloadManager( 3204): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/PhoneMonitor( 7020): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@290f5361 on behalf of 3204
,V/TelephonyAutoProfiling( 7020): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7020): [parse] Load xml
V/TelephonyAutoProfiling( 7020): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7020): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7020): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/art     ( 3891): Explicit concurrent mark sweep GC freed 2124(78KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 424us total 59.926ms
,I/CheckinService( 6847): Disabling old GoogleServicesFramework version
D/WeatherAncestor( 2754): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:8:5
V/DownloadManager( 3204): DownloadService onDestroy
,D/UpdateThreadPoolManager( 2754): 2 : This is isUpdating : false
D/WeatherAncestor( 2754): connectivity changed - connection : true
D/Weather_cast( 2754): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2754): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:8:5
D/WeatherService( 2754): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7084 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  972): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2754): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2754): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2754): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/CheckinService( 6847): Checking schedule, now: 1452283685161 next: 1452283679554
I/CheckinService( 6847): active receiver: enabled
,I/CheckinService( 6847): Preparing to send checkin request
I/EventLogService( 6847): Accumulating logs since 1452283641728
,W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     ( 6847): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6847): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/NotificationManager( 6847): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Babel_SMS( 7084): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7084): MmsConfig.loadMmsSettings
I/art     (  972): Explicit concurrent mark sweep GC freed 21286(1034KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.349ms total 142.761ms
,I/Babel_SMS( 7084): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7084): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7084): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7084): MmsConfig.loadFromResources
E/Babel_SMS( 7084): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7084): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 7084): CheckpointMarkThreadRoots callback created = 0xb042d4b0
D/SensorManager( 7084): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7084): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7084): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 7084): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7084): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7084): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7084): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7084): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7084): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7084): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7084): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7084): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7084): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7084): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7084): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7084): found sensor: Motion Accel, handle=46
I/art     ( 7084): CheckpointMarkThreadRoots callback created = 0xb042d4a0
,W/Settings( 7084): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7084): startup - clean
,I/Babel   ( 7084): deleted: false for 0
,I/CheckinRequestBuilder( 6847): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 6847): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager(  972): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7121 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  972): tsOffsetIs: Apps: 114690819283; DSPS: 3849231; Offset : -2782653322
W/AudioCapabilities( 7084): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7084): Unsupported mime audio/adpcm
W/AudioCapabilities( 7084): Unsupported mime audio/g726
W/AudioCapabilities( 7084): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7084): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7084): Unsupported mime video/mjpg
W/VideoCapabilities( 7084): Unsupported mime video/theora
,W/AudioCapabilities( 7084): Unsupported mime audio/evrc
,W/AudioCapabilities( 7084): Unsupported mime audio/qcelp
W/VideoCapabilities( 7084): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7084): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7084): Unsupported mime audio/qcelp
W/AudioCapabilities( 7084): Unsupported mime audio/evrc
,W/VideoCapabilities( 7084): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7084): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7084): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7084): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7084): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7084): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7084): onServiceConnected
,W/Babel   ( 7084): Attempted to change video mute state without an active call.
I/NotificationManager( 7084): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7084): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7084): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7084): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7084): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  273): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 7084): propertyValue:false
V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Babel   ( 7084): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  972): Killing 6811:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10048/pid_6811/cgroup.procs: No such file or directory
,I/ActivityManager(  972): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7150 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  972): Process com.google.android.music:main (pid 6918) has died
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7121): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7121): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7121): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7121): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7121): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7121):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7121):   adb logcat -s GAv4
W/ResourcesManager( 7150): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7150): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GAv4    ( 7121): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 7150): VM with version 2.1.0 has multidex support
I/MultiDex( 7150): install
I/MultiDex( 7150): VM has multidex support, MultiDex support library is disabled.
,W/GAv4    ( 7121): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7121): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/JNIHelp ( 7150): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7150): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7150): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15b21798: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7150): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7150): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7150): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 7150): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7150): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7150): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): CdmEngine::OpenSession
I/WVCdm   (  277): Level3 Library Dec 11 2014 16:13:16
I/WebViewFactory( 7121): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/WVCdm   (  277): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  277): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  277): L1 library not specified. Falling Back to L3
,I/LibraryLoader( 7121): Time to load native libraries: 2 ms (timestamps 5571-5573)
I/LibraryLoader( 7121): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7121): Binding Chromium to main looper Looper (main, tid 1) {302696c8}
I/LibraryLoader( 7121): Expected native library version number "",actual native library version number ""
I/chromium( 7121): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  277): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  277): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
D/WVCdm   (  277): PrepareKeyRequest: nonce=549304745
,I/BrowserStartupController( 7121): Initializing chromium process, singleProcess=true
W/art     ( 7121): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7121): ApplicationContext is null in ApplicationStatus
W/chromium( 7121): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/art     ( 7150): CheckpointMarkThreadRoots callback created = 0xb04cbe50
E/libEGL  ( 7121): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7121): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7121): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7121): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7121): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7121): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7121): Remote Branch: 
I/Adreno-EGL( 7121): Local Patches: 
I/Adreno-EGL( 7121): Reconstruct Branch: 
I/art     ( 7150): CheckpointMarkThreadRoots callback created = 0xb04cbe40
,V/AudioPolicyService(  277): registerClient() client 0xb57e7480, uid 10079
,W/AudioManagerAndroid( 7121): Requires BLUETOOTH permission
I/NSApplication( 7121): Starting up...
,I/ActivityManager(  972): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7215 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Process com.android.vending (pid 6829) has died
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/GCM     ( 1737): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 6847): Checkin interval check for package: unspecified last checkin: 1452283649596 min interval config: 0 actual interval: 37500
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/WearableService( 1737): callingUid 10006, callindPid: 1737
,E/MDM     ( 1737): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 6847): Restart initialization of location
,D/AuthorizationBluetoothService( 1737): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1737): com.google.android.gms: cancel(0) by com.google.android.gms
D/AuthorizationBluetoothService( 1737): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/GCoreFlp( 1737): No location to return for getLastLocation()
W/FusedLocationProvider( 1737): location=null
E/MDM     ( 1737): [106] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1737): com.google.android.gms: cancel(0) by com.google.android.gms
W/ContextImpl( 3554): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/LocationInitializer( 6847): Restart initialization of location
,W/GCoreFlp( 1737): No location to return for getLastLocation()
W/FusedLocationProvider( 1737): location=null
,W/IcingInternalCorpora( 6847): getNumBytesRead when not calculated.
,I/MusicWidget( 2719): mDelayedStopHandler : unbind
,I/MusicBrowser( 2107): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2107): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
,I/MusicBrowser( 2107): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2107): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2107): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2107): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2107): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2107): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  972):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3c0d54e4com.lge.music.MediaPlaybackService$6@2de2cd4d
,D/MusicBrowser( 2107): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2107): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2107): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2107): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2107): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2f482523
I/MusicBrowser( 2107): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2107): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2107): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2107): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,I/MusicBrowser( 2107): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
,I/MusicBrowser( 2107): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2107): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2107): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2107): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2107): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2107): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2107): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2107): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2107): reset
V/MediaPlayer[Native]( 2107): setListener
V/MediaPlayer[Native]( 2107): disconnect
V/MediaPlayer[Native]( 2107): destructor
,V/AudioFlinger(  277): releasing 19 from 2107 for -1
V/AudioFlinger(  277):  decremented refcount to 0
V/AudioFlinger(  277): purging stale effects
V/MediaPlayer[Native]( 2107): disconnect
D/MusicBrowser( 2107): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2107): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2107): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2107): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2107): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2107): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2107): [SmartShareManagerClient] unregisterListener: 984420354
W/SmartShareClient( 2107): [SmartShareManagerClient] unregisterListener invalid listener: 984420354
,I/SmartShareClient( 2107): [SmartShareManagerClient] terminate service: 2107/MediaPlaybackService/389193121
E/HomeCloudIF( 2107): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2107): [SmartShareManagerClient] unbindService context:android.app.Application@1a1c9d13
V/CloudHub( 2107): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2107): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2107): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2107): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2107): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
,I/ActivityManager(  972): Killing 6952:com.lge.email/u0a21 (adj 15): empty #11
I/CloudHub( 2107): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29995
W/libprocessgroup(  972): failed to open /acct/uid_10021/pid_6952/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WVCdm   (  277): CdmEngine::CloseSession
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  277): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  277): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
D/WVCdm   (  277): PrepareKeyRequest: nonce=1137766363
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WVCdm   (  277): CdmEngine::CloseSession
,I/WVCdm   (  277): L3 Terminate.
I/dex2oat ( 7266): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=38 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7266): dex2oat took 99.722ms (threads: 4)
,I/Adreno-EGL( 7150): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7150): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7150): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7150): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7150): Remote Branch: 
I/Adreno-EGL( 7150): Local Patches: 
I/Adreno-EGL( 7150): Reconstruct Branch: 
,I/Adreno-EGL( 7150): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7150): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7150): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7150): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7150): Remote Branch: 
I/Adreno-EGL( 7150): Local Patches: 
I/Adreno-EGL( 7150): Reconstruct Branch: 
,I/Adreno-EGL( 7150): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7150): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7150): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7150): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7150): Remote Branch: 
I/Adreno-EGL( 7150): Local Patches: 
I/Adreno-EGL( 7150): Reconstruct Branch: 
,I/CheckinRequestBuilder( 6847): Classify the device as Phone.
,D/libc-netbsd( 6847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 6847): propertyValue:false
,D/libc-netbsd( 6847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 6847): Sending checkin request (9844 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinRequestBuilder( 6847): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6847): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  972): Explicit concurrent mark sweep GC freed 14962(677KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.756ms total 139.652ms
,I/CheckinRequestBuilder( 6847): Classify the device as Phone.
,I/CheckinTask( 6847): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6847): Checking schedule, now: 1452283692994 next: 1452810941985
I/CheckinService( 6847): active receiver: disabled
,I/CheckinService( 6847): Checking schedule, now: 1452283693028 next: 1452810941985
I/CheckinService( 6847): active receiver: disabled
,D/CheckinService( 6847): Recording last checkin time for package unspecified as 1452283693037
,I/ActivityManager(  972): Killing 6668:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_6668/cgroup.procs: No such file or directory
,V/SetupWizard( 7020): Connected to Gservices successfully
I/ActivityManager(  972): Killing 6994:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10011/pid_6994/cgroup.procs: No such file or directory
,D/GCM     ( 1737): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  972): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1833): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1881): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,D/administrator(  972): Handling package changes for user 0
,I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7311 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationManager( 7084): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7084): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 7311): onCreate
W/AppUp4:DB( 7311):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7311):  setFingerPrint start
I/AppUp4:DB( 7311):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7311):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7311):  SDK version = 0
I/AppUp4:DB( 7311):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7311): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7311): onReceive
I/AppUp4:CustModeStarterReceiver( 7311): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7311): Context : android.app.ReceiverRestrictedContext@317ba208
D/AppUp4:CustFacade( 7311): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7311): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7311): begin check event
I/AppUp4:CustModeStarterReceiver( 7311): Event For Nothing, skip.
,V/JNIHelp ( 7084): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 7084): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7084): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  972): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7333 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/NotificationService(  972): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  972): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  972): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  972): Process com.google.android.apps.magazines (pid 7121) has died
,I/BackupManagerService(  972): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/LCardEmulationManager( 1791): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1791): getDefaultRoute
W/ResourcesManager(  972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/BackupManagerService(  972): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  972): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@219a48ae
W/ResourcesManager( 7333): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7333): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7333): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType(  972): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/AppConfig( 7333): Total System Memory = 906309632
,I/GalleryUtils( 7333): Application Heap = 96 MB
I/AppConfig( 7333): App Tier : NOT_DEF
,D/SystemHelper( 7333): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  972): Process com.android.chrome (pid 7215) has died
,I/[LGHome]EVENT( 1881): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  972): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7357 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.544ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.856ms
,I/GCoreNlp( 1737): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 32.811ms
,D/LocationProviderProxy(  972): applying state to connected service
W/ResourcesManager( 7357): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7357): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7357): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7357): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7357): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  972): Process com.google.android.apps.plus (pid 6565) has died
,I/SystemConfig( 7357): BUILD Country: EU
I/SystemConfig( 7357): BUILD Operator: OPEN
,I/SystemConfig( 7357): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7357): existFile = false
I/SystemConfig( 7357): canReadFile = false
I/SystemConfig( 7357): systemFeature RCS result false
D/SystemConfig( 7357): refreshRcsSupport() :false
,I/ActivityManager(  972): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7394 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/LockScreenSettings( 7394): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7394): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7394): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7394): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,D/LockScreenSettings( 7394): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7394): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  972): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7414 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7414): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1945): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  972): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7438 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Process com.google.android.gms.unstable (pid 7150) has died
,I/UpdateIcingCorporaServi( 1945): UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
,D/Finsky  ( 7438): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7438): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7438): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7438): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7438): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@28afa347 on behalf of 7438
,I/art     ( 3891): Explicit concurrent mark sweep GC freed 3184(130KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 359us total 28.046ms
,D/Finsky  ( 7438): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7438): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7438): Skipping gmscore version check
,D/Finsky  ( 7438): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/CloudHub( 2107): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19965
,D/Finsky  ( 7438): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 6847): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6847): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 6847): Storage manager: low false usage 1.76MB avail 2.36GB capacity 4.06GB
,I/Icing   ( 6847): updateResources: need to parse f{com.google.android.gms}
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1808): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/Icing   ( 6847): Internal init done: storage state 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
I/Icing   ( 6847): Post-init done
,D/charger_monitor(  492): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/Icing   ( 6847): updateResources: need to parse f{com.google.android.gms}
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Icing   ( 6847): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 6847): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6847): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  972): Killing 7047:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10051/pid_7047/cgroup.procs: No such file or directory
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  972): Killing 2107:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  277): 2107 died, releasing its sessions
V/AudioFlinger(  277):  pid 1756 @ 0
,V/AudioFlinger(  277):  pid 3187 @ 1
V/AudioFlinger(  277):  pid 3187 @ 2
W/libprocessgroup(  972): failed to open /acct/uid_10028/pid_2107/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/CheckinService( 6847): Done disabling old GoogleServicesFramework version
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 134691581305; DSPS: 4504616; Offset : -2782654032
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{18778c35 type 2 when 144643 com.google.android.gms} when 144643
,I/VacuumService( 1737): Vacuum at: now=1452283715950 tag=VacuumService
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/InstanceID/Rpc( 6847): Found 10006
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  972): ALS enabled for SRE
,D/PowerManagerServiceEx(  972): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28241 ms ago)
D/qdlights(  972): set_light_backlight: 252
,D/qdlights(  972): set_light_backlight: 249
D/qdlights(  972): set_light_backlight: 246
,D/qdlights(  972): set_light_backlight: 242
,D/qdlights(  972): set_light_backlight: 239
,D/qdlights(  972): set_light_backlight: 236
,D/qdlights(  972): set_light_backlight: 232
,D/qdlights(  972): set_light_backlight: 229
,D/qdlights(  972): set_light_backlight: 226
,D/qdlights(  972): set_light_backlight: 222
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
D/qdlights(  972): set_light_backlight: 219
,D/qdlights(  972): set_light_backlight: 216
,D/qdlights(  972): set_light_backlight: 212
,D/qdlights(  972): set_light_backlight: 209
,D/qdlights(  972): set_light_backlight: 206
,D/qdlights(  972): set_light_backlight: 202
,D/qdlights(  972): set_light_backlight: 199
,D/qdlights(  972): set_light_backlight: 196
,D/qdlights(  972): set_light_backlight: 192
,D/qdlights(  972): set_light_backlight: 189
,D/qdlights(  972): set_light_backlight: 186
,D/qdlights(  972): set_light_backlight: 182
,D/qdlights(  972): set_light_backlight: 179
,D/qdlights(  972): set_light_backlight: 176
,D/qdlights(  972): set_light_backlight: 172
,D/qdlights(  972): set_light_backlight: 169
,D/qdlights(  972): set_light_backlight: 166
,D/qdlights(  972): set_light_backlight: 162
,D/qdlights(  972): set_light_backlight: 159
,D/qdlights(  972): set_light_backlight: 156
,D/qdlights(  972): set_light_backlight: 152
,D/qdlights(  972): set_light_backlight: 149
,D/qdlights(  972): set_light_backlight: 146
,D/qdlights(  972): set_light_backlight: 142
,D/qdlights(  972): set_light_backlight: 139
,D/qdlights(  972): set_light_backlight: 136
,D/qdlights(  972): set_light_backlight: 132
,D/qdlights(  972): set_light_backlight: 129
,D/qdlights(  972): set_light_backlight: 126
,D/qdlights(  972): set_light_backlight: 122
,D/qdlights(  972): set_light_backlight: 119
,D/qdlights(  972): set_light_backlight: 116
,D/qdlights(  972): set_light_backlight: 112
,D/qdlights(  972): set_light_backlight: 109
,D/qdlights(  972): set_light_backlight: 106
,D/qdlights(  972): set_light_backlight: 102
,D/qdlights(  972): set_light_backlight: 99
,D/qdlights(  972): set_light_backlight: 96
,D/qdlights(  972): set_light_backlight: 92
,D/qdlights(  972): set_light_backlight: 89
,D/qdlights(  972): set_light_backlight: 86
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  972): set_light_backlight: 82
,D/qdlights(  972): set_light_backlight: 79
,D/qdlights(  972): set_light_backlight: 76
,D/qdlights(  972): set_light_backlight: 72
,D/qdlights(  972): set_light_backlight: 69
,D/qdlights(  972): set_light_backlight: 66
,D/qdlights(  972): set_light_backlight: 62
,D/qdlights(  972): set_light_backlight: 59
,D/qdlights(  972): set_light_backlight: 56
,D/qdlights(  972): set_light_backlight: 52
,D/qdlights(  972): set_light_backlight: 49
,D/qdlights(  972): set_light_backlight: 46
,D/qdlights(  972): set_light_backlight: 42
,D/qdlights(  972): set_light_backlight: 39
,D/qdlights(  972): set_light_backlight: 36
,D/qdlights(  972): set_light_backlight: 32
,D/qdlights(  972): set_light_backlight: 29
,D/qdlights(  972): set_light_backlight: 26
,D/qdlights(  972): set_light_backlight: 22
,D/qdlights(  972): set_light_backlight: 19
,D/qdlights(  972): set_light_backlight: 16
,D/qdlights(  972): set_light_backlight: 12
,D/qdlights(  972): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 154696578851; DSPS: 5160140; Offset : -2782661316
,I/PowerManagerService(  972): ALS enabled for SRE
D/PowerManagerServiceEx(  972): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35232 ms ago)
I/PowerManagerService(  972): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  972): ALS enabled for SRE
D/PowerManagerServiceEx(  972): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35241 ms ago)
W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  972): Sleeping (uid 1000)...
D/LPWGController(  972): [updateScreenState] screen on = false
D/LPWGController(  972): disable proximity sensor
,D/LPWGController(  972): enable proximity sensor
I/SensorManager(  972): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3565e722] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  972): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  972): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  972): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  972): activate: handle is 48, enable
,V/sensors_hal_Ctx(  972): activate sensors is 1400000000000
D/sensors_hal_Thresh(  972): enable: handle=48
I/sensors_hal_SAM(  972): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  972): waitForResponse: timeout=1000
V/sensors_hal_SAM(  972): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  972): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  972): enable: Received response: 0
D/PowerManagerServiceEx(  972): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35310 ms ago)
I/Adreno-EGL(  972): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  972): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  972): Build Date: 03/02/15 Mon
I/Adreno-EGL(  972): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  972): Remote Branch: 
I/Adreno-EGL(  972): Local Patches: 
I/Adreno-EGL(  972): Reconstruct Branch: 
,D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1002 us)
,I/Sensors (  441): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  972): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  972): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  972): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  972): processInd: handle 48, count=1
V/sensors_hal_Thresh(  972): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  972): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  972): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  972): poll: count: 256
I/sensors_hal_Ctx(  972): poll: released wakelock sensor_ind
D/sensors_hal_Util(  972): waitForResponse: timeout=0
D/LPWGController(  972): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  972): current mode = 1  value = 1 1
I/LPWGController(  972): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  972): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  972): set_light_backlight: 0
,I/SensorManager(  972): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  972): activate: handle is 46, disable
V/sensors_hal_Ctx(  972): activate sensors is 1000000000000
D/sensors_hal_LP2(  972): enable: handle=46
D/sensors_hal_LP2(  972): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  972): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  247): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  247): hwc_blank: Blanking display: 0
I/DisplayManagerService(  972): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  972): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  972): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  972): Display changed displayId=0
,D/DSDPConnection( 1756): Display #0 changed.
,D/qdhwcomposer(  247): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  972): Excessive delay in setPowerMode(): 200ms
I/qdhwcomposer(  247): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  972): Got set_interactive hint
,D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1374): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1334): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1334): notifyScreenOffLocked
D/SmartCoverViewMediator( 1334): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1374): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
,D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  972): Process com.google.android.talk (pid 7084) has died
D/WifiServerServiceExt(  972): sendKtScanInterval  mRtspPlay : false
,I/WifiServerServiceExt(  972): set CMD_KT_SCAN_INTERVAL
V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=on, calling pid 972
,D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=on
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
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/GpsLocationProvider(  972): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1833): |CORE| sendScreenState: state:true
I/LEDService( 1808): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1808): stopPatternFlashing()
D/LNfcService( 1791): action : android.intent.action.SCREEN_ON
D/qdlights( 1808): set_light_notifications: 0,0,0,0,3
I/LEDService( 1808): getCurrentHighestLGLedRecord : size = 1
,D/qdlights( 1808): set_light_notifications: 0,0,0,0,3
I/LEDService( 1808): updateLightsLocked : turn off led
D/qdlights( 1808): set_light_notifications: 0,0,0,0,3
D/NfcServiceNXP( 1791): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1791): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1791): isRequireNfcCRouting() return true
D/LNfcService( 1791): isHCERoutingtoHost() return : true
D/NfcService( 1791): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1791): mEnableLPD: true
D/NfcService( 1791): mEnableReader: false
D/NfcService( 1791): mEnableHostRouting: true
D/NfcService( 1791): newParams.techmask= mTechMask: default
D/NfcService( 1791): mEnableLPD: true
D/NfcService( 1791): mEnableReader: false
D/NfcService( 1791): mEnableHostRouting: true
D/NfcService( 1791): screenState= 3
D/NfcService( 1791): Discovery configuration equal, not updating.
I/Cliptray Service( 1808): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1808): lockStatus = 0
D/LEDHandler( 1808): RESTART MSG
D/SplitWindow(  972): check instance of lgWin Window{19678ae9 u0 SearchPanel}
,D/InputDispatcher(  972): Window went away: Window{28c3587f u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,D/Ulp_jni (  972): JNI:system_update. Event-0
,V/PhoneApp( 1756): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): ACTION_SCREEN_ON
,D/WeatherService( 2754): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 21:8:48,
D/WeatherService( 2754): 2 : ACTION screen on
D/WeatherService( 2754): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2754): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2754): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 21:8:48
,D/AppCleanupService( 4003): android.intent.action.SCREEN_ON
,V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=off, calling pid 972
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
D/WifiController(  972): CMD_SCREEN_OFF 
D/WifiController(  972): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  972): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
,I/Sensors (  441): sns_pwr.c(301):releasing wakelock
I/QCNEJ   ( 1833): |CORE| sendScreenState: state:false
,I/LEDService( 1808): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1808): stopPatternFlashing()
D/qdlights( 1808): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1808): clear
I/LEDService( 1808): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1808): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1791): action : android.intent.action.SCREEN_OFF
I/Cliptray Service( 1808): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1808): updateLightsLocked : turn on led
E/LEDService( 1808): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1808): Can't handle this request of patternId:0
D/LEDHandler( 1808): RESTART MSG
D/NfcServiceNXP( 1791): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1881): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1756): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): ACTION_SCREEN_OFF
D/WeatherService( 2754): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 21:8:48
D/WeatherService( 2754): 2 : ACTION screen off
D/WeatherService( 2754): 2 : TimeTick Receiver Unregister
D/WeatherService( 2754): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 21:8:48
D/AppCleanupService( 4003): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4003): AppUsageStatsSaveTask
E/NxpNfcJni( 1791): getReconnectState = 0x0
,D/LCardEmulationManager( 1791): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1791): getDefaultRoute
D/LNfcService( 1791): isRequireNfcCRouting() return true
D/LNfcService( 1791): isHCERoutingtoHost() return : true
D/NfcService( 1791): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1791): mEnableLPD: true
D/NfcService( 1791): mEnableReader: false
D/NfcService( 1791): mEnableHostRouting: true
D/NfcService( 1791): newParams.techmask= mTechMask: 0
D/NfcService( 1791): mEnableLPD: true
D/NfcService( 1791): mEnableReader: false
D/NfcService( 1791): mEnableHostRouting: true
D/NfcService( 1791): screenState= 1
E/NxpNfcJni( 1791): getReconnectState = 0x0
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{369f536e type 2 when 161220 com.android.systemui} when 161220
,D/PhoneUtils( 1756): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1756): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1756): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1756): getCallState : 0
,D/PhoneUtils( 1756): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1756): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1756): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 174697242073; DSPS: 5815522; Offset : -2782669612
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  972): acquireWakeLockInternal: lock=672932664, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=972
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{2563a0f type 2 when 187137 com.google.android.gms} when 187137
D/PowerManagerServiceEx(  972): releaseWakeLockInternal: lock=672932664 [*alarm*], flags=0x0
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1808): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
D/WifiController(  972): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/art     (  972): Explicit concurrent mark sweep GC freed 52302(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 3.490ms total 241.068ms
,I/PhenotypeConfigurator( 1737): Scheduling Phenotype for one-off execution 4324 seconds from now (1452283758790)
,D/GetConfigurationSnapshotOperation( 1737): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1737): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1737): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1737): Explicit concurrent mark sweep GC freed 46688(2MB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 13MB/22MB, paused 6.707ms total 140.631ms
,D/libc-netbsd( 1737): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1737): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1737): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1737): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
,I/System.out( 1737): propertyValue:false
,D/libc-netbsd( 1737): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1737): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1737): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1737): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{2ec88134 type 2 when 188553 android} when 188553
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 194698012013; DSPS: 6470907; Offset : -2782663211
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 214698781172; DSPS: 7126292; Offset : -2782656210
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 234699536060; DSPS: 7781677; Offset : -2782664496
,I/ClearcutLoggerApiImpl( 1737): disconnect managed GoogleApiClient
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1808): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  972): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 254700312407; DSPS: 8437062; Offset : -2782650905
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1808): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  972): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 274701089014; DSPS: 9092448; Offset : -2782667652
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 294701758538; DSPS: 9747830; Offset : -2782669748
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1808): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 314702428790; DSPS: 10403212; Offset : -2782670596
,I/jxcore-log( 5985): --= Surplus to requirements =--
I/jxcore-log( 5985): 
I/jxcore-log( 5985): ****TEST TOOK:  ms ****
I/jxcore-log( 5985): 
I/jxcore-log( 5985): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5985): 
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/AndroidRuntime( 7662): 
D/AndroidRuntime( 7662): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7662): CheckJNI is OFF
,D/AndroidRuntime( 7662): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  972): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  972): Killing 5985:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  972): WIN DEATH: Window{ce62c42 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  972): Skipping PackageSetting{7acea0b com.example.hello/10317} due to missing metadata
D/InputDispatcher(  972): Focus left window: Window{ce62c42 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  972): Window went away: Window{ce62c42 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  972):   Force finishing activity ActivityRecord{1598cdd7 u0 com.test.thalitest/.MainActivity t220}
,V/ActivityManager(  972): Display changed displayId=0
,D/DSDPConnection( 1756): Display #0 changed.
W/ActivityManager(  972): Spurious death for ProcessRecord{1366c2cc 5985:com.test.thalitest/u0a316}, curProc for 5985: null
,I/ActivityManager(  972): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,I/[LGHome]EVENT( 1881): [Launcher.java:5203:onStart()]onStart
,D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1881): [Launcher.java:776:onResume()]onResume
,I/InputReader(  972): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1833): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/GeofencerStateMachine( 1737): Ignoring removeGeofence because network location is disabled.
,W/System.err( 3554): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/ActivityManager(  972): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7687 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/System.err( 3554): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3554): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3554): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3554): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3554): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3554): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3554): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3554): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3554): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3554): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3554): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/[LGHome]EVENT( 1881): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1881): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1881): [Launcher.java:929:onResume()]onResume end
,W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/Activity( 1881): Activity.onPostResume() called 
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
,W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/art     ( 1945): Explicit concurrent mark sweep GC freed 9424(649KB) AllocSpace objects, 4(96KB) LOS objects, 39% free, 12MB/20MB, paused 3.379ms total 184.218ms
I/[LGHome]EVENT( 1881): [Launcher.java:986:onPause()]onPause
,D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1374): handleShortcutListChanged...
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
,W/[LGHome]LGWallpaperInfo( 1881): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1881): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
,W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
I/SystemUI[Framework](  972): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  972): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  972): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  972): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3c3c3289,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  972): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  972): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  972): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  972): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3c3c3289,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1374): handleShortcutListChanged...
D/InputDispatcher(  972): Focus entered window: Window{2c525582 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1881): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/art     (  972): Explicit concurrent mark sweep GC freed 19912(1406KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 3.023ms total 289.115ms
I/art     (  972): WaitForGcToComplete blocked for 195.436ms for cause Explicit
I/[LGHome]EVENT( 1881): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1881): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
W/ResourcesManager( 7687): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7687): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/PhoneWindow( 1881): [setNavigationBarColor] color=0x 0
,W/ResourcesManager( 7687): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/administrator(  972): Handling package changes for user 0
,I/NotificationService(  972): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  972): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  972): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  972): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
,W/InputMethodManagerService(  972): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  972): Got RemoteException sending setActive(false) notification to pid 5985 uid 10316
I/LGEmail ( 7687): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7687): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     (  972): Explicit concurrent mark sweep GC freed 6843(395KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.956ms total 291.330ms
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/Timeline(  972): Timeline: Activity_windows_visible id: ActivityRecord{3ca1881f u0 com.lge.launcher2/.Launcher t219} time:320031
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 1881): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1601): Unable to connect to the editor to retrieve text... will retry later
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1881): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1881): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1881): getTextAfterCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/LCardEmulationManager( 1791): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1791): getDefaultRoute
,D/AndroidRuntime( 7662): Shutting down VM
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
,W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
,W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/ResourcesManager(  972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/PackageChangeReceiver( 7687): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,W/ResourceType(  972): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/AppUp4:PreloadHelper( 7311): added Exclude : com.test.thalitest
,I/ActivityManager(  972): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7719 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,I/[LGHome]EVENT( 1881): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline( 1881): Timeline: Activity_idle id: android.os.BinderProxy@251485a4 time:320659
E/SharedPreferencesImpl( 1881): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
,W/ResourcesManager( 7719): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
