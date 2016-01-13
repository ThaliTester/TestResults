#### Test 55902202f27eba5_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/Icing   ( 4259): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
--------- beginning of system
V/AlarmManager(  850): ELAPSED_WAKEUP set : Alarm{1ae996b type 2 when 91705 com.android.providers.calendar} when 91705
,I/ActivityManager(  850): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6096 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  850): Killing 5879:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_10053/pid_5879/cgroup.procs: No such file or directory
W/ResourcesManager( 6096): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/CalendarProvider2( 6096): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1fc82b93
D/CalendarProvider2( 6096): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6096): Created com.android.providers.calendar.CalendarAlarmManager@51150fc(com.android.providers.calendar.CalendarProvider2@1fc82b93)
D/CalendarProviderBroadcastReceiver( 6096): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6096): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6096): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6096): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6096): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 6096): [IntentService] Release Lock
D/CalendarProvider2( 6096): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  850): Killing 5987:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_10011/pid_5987/cgroup.procs: No such file or directory
D/AndroidRuntime( 6112): 
D/AndroidRuntime( 6112): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6112): CheckJNI is OFF
D/AndroidRuntime( 6112): Calling main entry com.android.commands.am.Am
I/ActivityManager(  850): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  850): setTaskToReturnTo : TaskRecord{12a2cae3 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  850): setTaskToReturnTo : TaskRecord{12a2cae3 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  850): AppWindowTokenEx init.. 
D/ContextHelper(  850): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  850): check instance of lgWin Window{147c70c u0 Starting com.test.thalitest}
D/InputDispatcher(  850): Focus left window: Window{31037a9d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6112): Shutting down VM
I/ActivityManager(  850): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6141 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1939): Closing mic
I/MicrophoneInputStream( 1939): mic_close com.google.android.apps.gsa.speech.audio.u@2b13b1bd
V/AudioRecord( 1939): stop()
D/AudioRecord( 1939): AudioRecord->stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioFlinger(  279): Record stopped OK
V/AudioPolicyManager(  279): stopInput() input 16
V/AudioPolicyService(  279): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  279): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  279): ThreadBase::setParameters() routing=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb410e000
D/audio_hw_primary(  279): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  850): Starting window displayed
I/SystemUI[Framework](  850): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  850): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  850): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  850): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@83bedf7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
V/audio_hw_primary(  279): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  279): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  279): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  279): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  279): disable_audio_route: exit
E/audio_hw_primary(  279): disable_snd_device: enter 144
D/hardware_info(  279): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  279): disable_snd_device: snd_device(144: lg-vr-handset-mic)
D/BarTransitions( 1374): draw background and invalidate : color = 13000000
D/BarTransitions( 1374): draw background and invalidate : color = 11111111
V/audio_hw_primary(  279): stop_input_stream: exit: status(0)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
,V/AudioPolicyManager(  279): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  279): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  279): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  279): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  279): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  279): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  279): setParameters(): io 16, keyvalue hotword_active=0, calling pid 279
V/AudioFlinger(  279): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  279): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  279): in_set_parameters: exit: status(0)
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb410e000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 16
V/AudioPolicyManager(  279): closeInput(16)
V/AudioFlinger(  279): closeInput() 16
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  850): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  279): ThreadBase::exit
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): RecordThread 0xb410e000 exiting
V/AudioSystem( 3274): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1749): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1939): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1968): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2718): ioConfigChanged() event 4, ioHandle 16
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb40367a0)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioFlinger(  279): removeClient_l() pid 1939, calling pid 279
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioFlinger(  279): releasing 15 from 1939 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
I/HotwordRecognitionRnr( 1939): Stopping hotword detection.
I/HotwordRecognitionRnr( 1939): Hotword detection finished
D/ContextHelper( 6141): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6141): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6141): Time to load native libraries: 3 ms (timestamps 3200-3203)
I/LibraryLoader( 6141): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6141): Binding Chromium to main looper Looper (main, tid 1) {51150fc}
I/LibraryLoader( 6141): Expected native library version number "",actual native library version number ""
I/chromium( 6141): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6141): Initializing chromium process, singleProcess=true
W/art     ( 6141): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6141): ApplicationContext is null in ApplicationStatus
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
W/chromium( 6141): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6141): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6141): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6141): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6141): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6141): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6141): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6141): Remote Branch: 
I/Adreno-EGL( 6141): Local Patches: 
I/Adreno-EGL( 6141): Reconstruct Branch: 
V/AudioPolicyService(  279): registerClient() client 0xb4027160, uid 10316
D/BluetoothManagerService(  850): Message: 20
D/BluetoothManagerService(  850): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a9d292f:true
D/BluetoothAdapterService(832602344)( 1968): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1074a37e
D/AlertService( 5940): Beginning updateAlertNotification
D/AlertService( 5940): No fired or scheduled alerts
I/NotificationManager( 5940): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(11) by com.android.calendar
,I/NotificationManager( 5940): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5940): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5940): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 5940): No events found starting within 1 week.
,W/art     ( 6141): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6141): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6141): CordovaWebView is running on device made by: LGE
,W/art     ( 6141): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6141): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 6141): Activity.onPostResume() called 
,D/OpenGLRenderer( 6141): Render dirty regions requested: true
I/OpenGLRenderer( 6141): Initialized EGL, version 1.4
D/OpenGLRenderer( 6141): Enabling debug mode 0
,D/Atlas   ( 6141): Validating map...
,D/SplitWindow(  850): check instance of lgWin Window{2030bc1f u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6141): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  850): Killing 5940:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_10013/pid_5940/cgroup.procs: No such file or directory
,D/InputDispatcher(  850): Focus entered window: Window{2030bc1f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  850): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  850): Displayed com.test.thalitest/.MainActivity: +1s210ms
I/Timeline(  850): Timeline: Activity_windows_visible id: ActivityRecord{17b3bce0 u0 com.test.thalitest/.MainActivity t222} time:93931
,I/Timeline( 6141): Timeline: Activity_idle id: android.os.BinderProxy@3aefbfb time:93943
,W/BindingManager( 6141): Cannot call determinedVisibility() - never saw a connection for the pid: 6141
,I/ActivityManager(  850): Killing 5653:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  850): failed to open /acct/uid_10061/pid_5653/cgroup.procs: No such file or directory
,W/ActivityManager(  850): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  850): RTC_WAKEUP set : Alarm{32af2258 type 0 when 1452526470027 com.android.providers.contacts} when 1452526470027
,V/AlarmManager(  850): ELAPSED_WAKEUP set : Alarm{19189fb1 type 2 when 60481 com.google.android.talk} when 60481
D/JsMessageQueue( 6141): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  850): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6228 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
V/AlarmManager(  850): RTC_WAKEUP set : Alarm{1f081017 type 0 when 1452699327874 com.android.vending} when 1452699327874
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 94588383667; DSPS: 3197531; Offset : -2997304369
D/Finsky  ( 5540): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6228): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationManager(  850): android: cancelAsUser(2) by android
D/jxcore_app_log( 6141): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622850048
,D/JX-Cordova( 6141): jxcore cordova android initializing
D/libc-netbsd( 5540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 5540): propertyValue:false
,D/libc-netbsd( 5540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 6141): CheckpointMarkThreadRoots callback created = 0x9a4ffbd0
,I/art     ( 6141): CheckpointMarkThreadRoots callback created = 0x9a4ffba0
D/libc-netbsd( 5540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Babel_SMS( 6228): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6228): MmsConfig.loadMmsSettings
I/Babel_SMS( 6228): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/Babel_SMS( 6228): MmsConfig.loadFromDatabase
E/Babel_SMS( 6228): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6228): MmsConfig.loadFromResources
E/Babel_SMS( 6228): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6228): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6228): CheckpointMarkThreadRoots callback created = 0xaaf22f00
,D/SensorManager( 6228): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6228): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6228): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6228): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6228): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6228): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6228): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6228): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6228): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6228): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6228): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6228): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6228): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6228): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6228): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6228): found sensor: Motion Accel, handle=46
,W/Settings( 6228): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 6228): CheckpointMarkThreadRoots callback created = 0xaaf22ef0
I/Babel_Crash( 6228): startup - clean
I/Babel   ( 6228): deleted: false for 0
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  850): android: cancelAsUser(2) by android
,I/qtaguid ( 5540): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5540): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5540): untagSocket(41) failed with errno -22
W/AudioCapabilities( 6228): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6228): Unsupported mime audio/adpcm
W/AudioCapabilities( 6228): Unsupported mime audio/g726
W/AudioCapabilities( 6228): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6228): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6228): Unsupported mime video/mjpg
D/Finsky  ( 5540): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,W/VideoCapabilities( 6228): Unsupported mime video/theora
W/AudioCapabilities( 6228): Unsupported mime audio/evrc
,W/AudioCapabilities( 6228): Unsupported mime audio/qcelp
W/VideoCapabilities( 6228): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6228): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6228): Unsupported mime audio/qcelp
W/AudioCapabilities( 6228): Unsupported mime audio/evrc
I/ActivityManager(  850): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6260 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:28.992 DNS addrs= 192.168.1.1, 0.0.0.0, 
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NotificationManager(  850): android: cancelAsUser(2) by android
W/VideoCapabilities( 6228): Unsupported mime video/mp4v-esdp
,W/ResourcesManager( 6260): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6260): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/VideoCapabilities( 6228): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6228): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6228): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6228): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6228): Unrecognized profile 2130706433 for video/avc
,W/SQLiteConnectionPool( 4259): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/MultiDex( 6260): VM with version 2.1.0 has multidex support
I/MultiDex( 6260): install
I/MultiDex( 6260): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6260): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/vclib   ( 6228): onServiceConnected
,W/Babel   ( 6228): Attempted to change video mute state without an active call.
W/ResourcesManager( 6228): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6228): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityThread( 6260): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6260): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@165bb8de: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6260): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6260): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6260): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4259): Restart initialization of location
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/ChimeraCfgMgr( 6260): Reading stored module config
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/JNIHelp ( 6228): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
D/ChimeraCfgMgr( 6260): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/System  ( 6228): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6228): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6228): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/CAR.SERVICE( 6260): Connecting to CarCallService...
,D/NativeLibraryUtils( 6260): Install completed successfully. count=14 extracted=0
I/art     ( 6260): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6260): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/qtaguid ( 5540): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5540): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5540): untagSocket(41) failed with errno -22
D/CAR.SERVICE( 6260): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6260): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6260): Creating a new PhoneAdapter instance
W/ActivityManager(  850): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6260): setListener: com.google.android.gms.car.dn@388bad45
W/ActivityManager(  850): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6260): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6260): Starting CarCallService with initial phone null
I/NotificationManager( 6260): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6260): Package validated; name: com.android.vending
,I/NotificationManager( 5540): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5540): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/art     ( 5540): CheckpointMarkThreadRoots callback created = 0xb0583580
,I/art     ( 5540): CheckpointMarkThreadRoots callback created = 0xb0583540
,I/ActivityManager(  850): Process com.android.contacts (pid 6032) has died
,I/ActivityManager(  850): Process com.android.gallery3d (pid 6009) has died
,W/jxcore-log( 6141): Initializing JXcore engine
,W/jxcore-log( 6141): JXcore engine is ready
,W/art     ( 5540): Suspending all threads took: 6.330ms
W/jxcore-log( 6141): Starting JXcore engine
W/.test.thalitest( 6141): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6265]" dev="sockfs" ino=6265 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6141): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6141): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8286]" dev="sockfs" ino=8286 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6141): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6141): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6141): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[28967]" dev="sockfs" ino=28967 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 6141): Platform android
W/jxcore-log( 6141): 
W/jxcore-log( 6141): Process ARCH arm
W/jxcore-log( 6141): 
I/NotificationManager(  850): android: cancelAsUser(2) by android
,I/qtaguid ( 5540): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5540): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5540): untagSocket(41) failed with errno -22
,W/ResourcesManager( 5540): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5540): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5540): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5540): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  850): RTC_WAKEUP set : Alarm{24e67719 type 0 when 1452699331272 com.android.vending} when 1452699331272
,V/AlarmManager(  850): RTC_WAKEUP set : Alarm{29d9f9bf type 0 when 1452699331324 com.google.android.googlequicksearchbox} when 1452699331324
,D/DeviceConnectionService( 1732): client connected with version: 8296000
,D/Finsky  ( 5540): [680] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5540): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5540): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  850): android: cancelAsUser(2) by android
,D/libc-netbsd( 5540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 5540): propertyValue:false
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6141): JXcore Cordova bridge is ready!
I/jxcore-log( 6141): 
W/jxcore-log( 6141): JXcore engine is started
,I/Choreographer( 6141): Skipped 213 frames!  The application may be doing too much work on its main thread.
I/chromium( 6141): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 6141): Toggling radios to true
I/jxcore-log( 6141): 
,D/BluetoothAdapter( 6141): enable(): BT is already enabled..!
D/WifiServiceImplEx(  850): setWifiEnabled: true pid=6141, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  850): setWifiEnabled: true pid=6141, uid=10316
D/WifiServiceImplEx(  850): disconnect pid=6141, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  850): reconnect pid=6141, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 6141): Radios toggled
I/jxcore-log( 6141): 
I/jxcore-log( 6141): My device name is: LGE-LG-D722
I/jxcore-log( 6141): 
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2821): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/wpa_supplicant( 2821): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
E/WifiStateMachine(  850): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1803): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  850): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  850): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  850): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  850): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  275): Clearing all IP addresses on wlan0
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1732): Read error: ssl=0xaaef8200: I/O error during system call, Connection timed out
,D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  850): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  850): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  850): hidePasspointNotification off =false
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:31.99 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,I/ActivityManager(  850): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6343 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
E/WifiStateMachine(  850): Start Disconnecting Watchdog 1
D/WifiHS20(  850): hidePasspointNotification off =false
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  850): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/LGWifiP2pService(  850): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:32.054 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2821): wlan0: CTRL-EVENT-SCAN-STARTED 
D/CommandListener(  275): Clearing all IP addresses on wlan0
,D/ConnectivityService(  850): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  850): disableDataServiceNotify
D/WifiHS20(  850): hidePasspointNotification off =false
D/DSQN    (  850): stop dsqn bin
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  850): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  850):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  850):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:32.112 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  850): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524292
,D/Nat464Xlat(  850): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/DhcpStateMachine(  850): StoppedState
D/DhcpStateMachine(  850): StoppedState{ when=-61ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/CSLegacyTypeTracker(  850): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  850): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): ValidatedState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): DefaultState{ when=-11ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): Disconnected - quitting
D/ConnectivityService(  850): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  850): MasterInitialState.processMessage what=3
V/NetworkPolicy(  850): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  850): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  850): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/QCNEJ   ( 1839): |CORE| No family connected
D/ConnectivityService(  850): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  850): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  850): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  850): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  850): MasterInitialState.processMessage what=3
,D/WifiNetworkAgent(  850): NetworkAgent: NetworkAgent channel lost
D/TelephonyNetworkFactory-1( 1749): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  850): Removing idletimer
W/Settings(  850): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiHS20(  850): hidePasspointNotification off =false
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/ConnectivityService(  850): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = -1
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:32.165 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:32.171 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  850): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  850): setSupplicantStateDISCONNECTED
D/WIFI    (  850): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  850):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt(  850): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  850): setSupplicantStateSCANNING
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/art     (  850): Suspending all threads took: 6.813ms
,D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     (  850): Explicit concurrent mark sweep GC freed 35209(1698KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 10.421ms total 304.519ms
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
V/NativeCrypto( 1732): SSL shutdown failed: ssl=0xaaef8200: I/O error during system call, Broken pipe
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,W/ResourcesManager( 6343): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6343): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 6343): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6343): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6343): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6343): Using schema version: 115
,I/IndexDatabaseHelper( 6343): Index is fine
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
I/ActivityManager(  850): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6371 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6371): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6371): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6371): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
I/PCSuite ( 6371): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6371): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6371): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
I/PCSuite ( 6371): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6371): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6371): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
I/PCSuite ( 6371): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6371): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6371): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
I/ActivityManager(  850): Process com.google.android.apps.plus (pid 5844) has died
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2821): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:33.23 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/LocSvc_java(  850): onReceive
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2821): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [SCANNING]
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  850): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt(  850): setSupplicantStateASSOCIATED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:33.259 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,I/wpa_supplicant( 2821): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2821): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:33.282 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:33.289 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,D/WiFiOffLoadBroadcast( 6343): Not supported operator for automatic switch
I/WifiServiceExtension(  850): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt(  850): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt(  850): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  850): setSecurityType  : 2
,D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
I/ActivityManager(  850): Process com.android.providers.calendar (pid 6096) has died
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:33.414 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:33.421 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  850): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  850): Got NetworkAgent Messenger
,D/ConnectivityService(  850): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  850): NetworkAgent connected
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
E/WifiConfigStore(  850): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
E/WifiConfigStore(  850): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 9
,D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  275): Setting iface cfg
E/WifiStateMachine(  850): Start Dhcp Watchdog 2
D/DhcpStateMachine(  850): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  850): WaitBeforeStartState
D/WifiServerServiceExt(  850): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  850): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  850): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  850): setSupplicantStateGROUP_HANDSHAKE
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  850): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt(  850): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  850): setSupplicantStateCOMPLETED
D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
E/WifiStateMachine(  850): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  850): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  850): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@88a80bb target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  850): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@88a80bb target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  850): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  850): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  850): DHCP Start wake lock is acquired.
D/CommandListener(  275): Setting iface cfg
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  275): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  850): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/ConnectivityService(  850): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt(  850): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  850): setSupplicantStateCOMPLETED
D/LGWifiP2pService(  850): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  850): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  850): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  850): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  850): ignoring duplicate network state non-change
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:33.592 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:33.598 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  850): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  850): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/WifiHS20(  850): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 3
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
D/WifiHS20(  850): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine(  850): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:33.623 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  850): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:33.63 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
E/ConnectivityService(  850): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  850): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  850): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
E/Netd    (  275): netlink response contains error (File exists)
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  850): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 3
D/ConnectivityService(  850): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  850): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  850): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  850): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  850): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  850): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  850): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  850):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  850):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  850):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  850):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  850):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  850): currentScore = 0, newScore = 20
D/ConnectivityService(  850):    accepting network in place of null
D/ConnectivityService(  850): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1749): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  850): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  850):   my score=60,, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  850): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  850): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  850): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  850): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  850): [e] list.add(nai) empty : false size: 1
D/Tethering(  850): MasterInitialState.processMessage what=3
D/ConnectivityService(  850): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  850): validation of new default Network = false
D/ConnectivityService(  850): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  850): enableDataServiceNotify 
D/DSQN    (  850): start dsqn bin
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
I/PCSuite ( 6371): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): [LWD] Start DNSResolver start to wait
V/NetworkPolicy(  850): [LG_RESTRICTED] checkMobilePolicy_type()
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): [LWD] wait 500ms before dns check
D/PCSuite ( 6371): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6343): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6343): MCCMNC not supported: null
I/PCSuite ( 6371): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/ConnectivityService(  850): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  850):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  850):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/PCSuite ( 6371): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/ConnectivityService(  850): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
I/DSQN    ( 6411): DSQN samuel.seo ver 141203
E/DSQN    ( 6411): DSQN sock connect success to lgdatalistenerd
,I/DSQN    ( 6411): created command queue thread
I/DSQN    ( 6411): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6411): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/DhcpStateMachine(  850): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  850): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  850): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6414): version 5.5.6 starting
E/dhcpcd  ( 6414): get_duid: Read-only file system
,I/dhcpcd  ( 6414): wlan0: rebinding lease of 192.168.1.134
,I/dhcpcd  ( 6414): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6414): wlan0: leased 192.168.1.134 for 86400 seconds
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): [LWD] DNSResolver start dns
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out(  850): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6411): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6411): restart monitoring
,D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6411): dsqn report finish
D/DSQN    (  850): DSQM DsqnNotification wlan0  1
D/DSQN    (  850): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 15:35:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452699334295], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452699334278]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  850): Validated
D/ConnectivityService(  850): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  850): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  850):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  850):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  850):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  850): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  850): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  850):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  850):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  850): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  850): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  850): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  850):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1749): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  850): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiDataContinuityService(  850): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  850): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  850): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  850): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  850): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  850): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  850): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  850): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  850): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  850): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  850): RunningState
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  850): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/CAR.SERVICE( 6260): mConnectedToCar = false, abort
,E/ActivityThread( 6260): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2c37d98d that was originally bound here
E/ActivityThread( 6260): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2c37d98d that was originally bound here
E/ActivityThread( 6260): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6260): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6260): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6260): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6260): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6260): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6260): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6260): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6260): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6260): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6260): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6260): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6260): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6260): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6260): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6260): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6260): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6260): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6260): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6260): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6260): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6260): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6260): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6260): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@207e59bc that was originally bound here
E/ActivityThread( 6260): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@207e59bc that was originally bound here
E/ActivityThread( 6260): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6260): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6260): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6260): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6260): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6260): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6260): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6260): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6260): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6260): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6260): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6260): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6260): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6260): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6260): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6260): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6260): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6260): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6260): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6260): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6260): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6260): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  850): Unbind failed: could not find connection for android.os.BinderProxy@34c78754
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  850): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  850): identical MTU - not setting
D/Nat464Xlat(  850): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  850): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  850):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  850):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  850): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  850): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  850): enableDataServiceNotify 
D/DSQN    (  850): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524295
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:35.13 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/DSQN    (  850): dsqn is running restart
D/ConnectivityService(  850): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  850): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  850): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  850): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/DSQN    ( 6458): DSQN samuel.seo ver 141203
E/DSQN    ( 6458): DSQN sock connect success to lgdatalistenerd
,I/DSQN    ( 6458): created command queue thread
I/DSQN    ( 6458): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6458): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/LocSvc_java(  850): onReceive
D/LocSvc_java(  850): got connectivity action
,D/LocSvc_java(  850): broadcast - no network connections
D/LocSvc_java(  850): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  850): Sending msg: 4 arg1:0 arg2:1
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/ActivityManager(  850): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6469 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocSvc_java(  850): onReceive
D/LocSvc_java(  850): got connectivity action
D/LocSvc_java(  850): broadcast - no network connections
D/LocSvc_java(  850): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  850): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  850): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  850): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  850): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  850): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  850): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  850): ignore wifi update if we are not in OPENING or CLOSING
V/AlarmManager(  850): ELAPSED_WAKEUP set : Alarm{32866fd type 2 when 101862 com.google.android.gms} when 101862
D/GpsLocationProvider(  850): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  850): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/MusicStore( 6469): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6469): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6469): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6469): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6469): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6469): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6469): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6469): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6469): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d8e7431: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6469): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6469): GMSCore installation verified
,I/ConfigStore( 6469): Config Database version: 1
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/MediaRouter( 6469): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
V/MusicLeanback( 6469): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6469): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6469): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  850): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6510 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/GHttpClientFactory( 6469): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6469): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  850): Killing 6054:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/ResourcesManager( 6510): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6510): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6510): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  850): failed to open /acct/uid_10069/pid_6054/cgroup.procs: No such file or directory
,I/NotificationManager( 6469): com.google.android.music: cancel(1061) by com.google.android.music
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:36.489 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NotificationManager( 1939): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
I/LGEmail ( 6510): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,V/WifiInternetCheck(  850): Single check msg out of sync, ignoring.
,D/LGEmail ( 6510): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/ConnectivityService(  850): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  850): onReceive
D/LocSvc_java(  850): got connectivity action
D/LocSvc_java(  850): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  850): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  850): getAGpsConnectionInfo connType - 4
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  850): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  850): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  850): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 6469): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider(  850): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/eas_req ( 6510): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  850): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6544 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 22.326ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 20.828ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.107ms
,I/HubEmail( 6510): JNI_OnLoad()
I/HubEmail( 6510): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6510): registerNatives()
I/HubEmail( 6510): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6510): registerNativeMethods()
I/HubEmail( 6510): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6510): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  850): Killing 6260:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_10006/pid_6260/cgroup.procs: No such file or directory
,W/Settings( 6510): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6544): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6544): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6544): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6544): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6544): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6544): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  850): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6565 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 6544): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6544): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6544): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 ,
,E/LGDMClient( 6544): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6544): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6544): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6544): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6544): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  850): Killing 5540:com.android.vending/u0a36 (adj 15): empty #11
,I/AppUp4:AppBoxCP( 6565): onCreate
,W/AppUp4:DB( 6565):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6565):  setFingerPrint start
I/AppUp4:DB( 6565):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6565):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6565):  SDK version = 0
I/AppUp4:DB( 6565):  beforefinger == newfinger no write in DB
W/libprocessgroup(  850): failed to open /acct/uid_10036/pid_5540/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6565): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6565): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 6565): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6565): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6565): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6565): onReceive
I/AppUp4:CustModeStarterReceiver( 6565): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6565): Context : android.app.ReceiverRestrictedContext@df47385
D/AppUp4:CustFacade( 6565): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6565): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6565): begin check event
I/AppUp4:CustModeStarterReceiver( 6565): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6565): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6565): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6565): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6565): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  850): Killing 6228:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_10061/pid_6228/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3274): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3274): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3274): networkInfo.isConnected() = false
I/ActivityManager(  850): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6591 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PhoneMonitor( 6591): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6591): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6591): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  850): Killing 6343:com.android.settings/1000 (adj 15): empty #11
,D/PhoneMonitor( 6591): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6591): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6591): [parse] Load xml
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
V/TelephonyAutoProfiling( 6591): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6591): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6591): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_6343/cgroup.procs: No such file or directory
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  850): propertyValue:false
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  850): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  850): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  850): propertyValue:false
I/CheckinService( 4259): Checkin interval check for package: unspecified last checkin: 1452699312345 min interval config: 0 actual interval: 25533
V/DownloadManager( 3225): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3225): DownloadService onCreate
I/DSQN    ( 6458): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6458): restart monitoring
I/DSQN    ( 6458): dsqn report finish
D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  850): DSQM DsqnNotification wlan0  1
D/DSQN    (  850): start to monitor internet connection
I/DownloadManager( 3225): in removeSpuriousFiles
,I/NotificationManager( 3225): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3225): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3225): created cursor android.database.sqlite.SQLiteCursor@28328360 on behalf of 3225
I/DownloadManager( 3225): in trimDatabase
V/DownloadManager( 3225): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3225): created cursor android.database.sqlite.SQLiteCursor@3dc96019 on behalf of 3225
,V/WifiInternetCheck(  850): isHttpConnectionAvailable - We got a valid response : 204
I/ActivityManager(  850): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6618 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/CheckinService( 4259): Checking schedule, now: 1452699337921 next: 1452699342307
I/CheckinService( 4259): active receiver: disabled
V/DownloadManager( 3225): DownloadService onStartCommand
,V/DownloadManager( 3225): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3225): created cursor android.database.sqlite.SQLiteCursor@252c758c on behalf of 3225
,V/DownloadManager( 3225): DownloadService onDestroy
,I/ActivityManager(  850): Killing 5698:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5091): android.os.DeadObjectException
,W/System.err( 5091): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5091): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5091): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5091): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5091): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5091): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5091): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5091): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5091): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5091): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5091): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5091): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5091): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5091): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5091): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5091): android.os.DeadObjectException
W/System.err( 5091): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5091): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5091): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5091): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5091): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5091): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5091): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5091): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5091): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5091): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5091): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5091): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5091): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5091): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5091): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  850): failed to open /acct/uid_10089/pid_5698/cgroup.procs: No such file or directory
W/ActivityManager(  850): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/WeatherAncestor( 2667): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:35:38
I/ActivityManager(  850): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6645 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UpdateThreadPoolManager( 2667): 2 : This is isUpdating : false
D/WeatherAncestor( 2667): connectivity changed - connection : true
D/Weather_cast( 2667): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2667): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:35:38
,D/WeatherService( 2667): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  850): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6662 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  850): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2667): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2667): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2667): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6645): Quickset Services start...
I/UEI.SmartControl( 6645): Manufacture = LGE
,W/ResourcesManager( 6662): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6645): File observer start...
E/UEI.SmartControl( 6645): IR Port is disabled: false
D/UEI.SmartControl( 6645): Starting file observer...
D/UEI.SmartControl( 6645): Extracting JNI libs...
D/UEI.SmartControl( 6645): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6645): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6645): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6645): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6645): --- Selecting new region: 2
I/UEI.SmartControl( 6645): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6645): Platform has CIR...
D/UEI.SmartControl( 6645): NO CIR support, need to check package...
I/UEI.SmartControl( 6645): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6645): QS Service created
,E/UEI.SmartControl( 6645): QS start get config
,D/UEI.SmartControl( 6645): Loading JNI Libs...
,D/UEI.SmartControl( 6645):  configuring local db...
I/Babel_SMS( 6662): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6662): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6662): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6662): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6662): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6662): MmsConfig.loadFromResources
E/Babel_SMS( 6662): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6662): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6662): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6662): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6662): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6662): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6662): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6662): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6662): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6662): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6662): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6662): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6662): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6662): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6662): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6662): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6662): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6662): found sensor: Motion Accel, handle=46
,I/art     ( 6662): CheckpointMarkThreadRoots callback created = 0xaaf22390
W/Settings( 6662): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6662): startup - clean
I/Babel   ( 6662): deleted: false for 0
,I/art     ( 6662): CheckpointMarkThreadRoots callback created = 0xaaf22370
D/UEI.SmartControl( 6645):  ---- Has DB8: true
D/UEI.SmartControl( 6645): QS start statue = true Error code = 0
D/UEI.SmartControl( 6645): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6645): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6645): IRRCDataComm has AudioManager!!!!.
I/ActivityManager(  850): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6696 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/irrc_jni( 6645): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6645): IrrcClient ++ 
D/irrcClient( 6645): getIrrcService ++ 
D/irrcClient( 6645): getIrrcService -- 
D/irrcClient( 6645): IrrcClient -- 
W/irrc_jni( 6645): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6645): Services init done
I/UEI.SmartControl( 6645): Device manager: loading config....
D/UEI.SmartControl( 6645): QS Service init finished
,D/UEI.SmartControl( 6645): Config is loaded...
D/UEI.SmartControl( 6645): QS Service version name: 0.1.73
D/UEI.SmartControl( 6645): QS Service version code: 1073
D/UEI.SmartControl( 6645): Service requested: Control
I/ActivityManager(  850): Killing 6371:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6645): -----IControl: 11
,D/UEI.SmartControl( 6645): Caller: com.lge.qremote
D/UEI.SmartControl( 6645): ------------ IControl registerCallback...
W/AudioCapabilities( 6662): Unsupported mime audio/x-lg-flac
I/UEI.SmartControl( 6645): Registering callback...
D/UEI.SmartControl( 6645): -----IControl: 19
D/UEI.SmartControl( 6645): Caller: com.lge.qremote
I/UEI.SmartControl( 6645): Registering Services Ready callback...
I/UEI.SmartControl( 6645): Notify client services are ready...
D/UEI.SmartControl( 6645):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6645): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6645): -----IControl: 8
,D/UEI.SmartControl( 6645): Caller: com.lge.qremote
W/AudioCapabilities( 6662): Unsupported mime audio/adpcm
W/AudioCapabilities( 6662): Unsupported mime audio/g726
W/AudioCapabilities( 6662): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6662): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6662): Unsupported mime video/mjpg
,W/VideoCapabilities( 6662): Unsupported mime video/theora
W/AudioCapabilities( 6662): Unsupported mime audio/evrc
,W/AudioCapabilities( 6662): Unsupported mime audio/qcelp
W/VideoCapabilities( 6662): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6662): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6662): Unsupported mime audio/qcelp
W/AudioCapabilities( 6662): Unsupported mime audio/evrc
W/VideoCapabilities( 6662): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6662): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6662): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6662): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6662): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_6371/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6645): Internal service binding...
W/VideoCapabilities( 6662): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6662): onServiceConnected
W/Babel   ( 6662): Attempted to change video mute state without an active call.
,I/NotificationManager( 6662): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6662): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6662): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6662): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6662): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out( 6662): propertyValue:false
I/Babel   ( 6662): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  850): Process com.google.android.music:main (pid 6469) has died
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:39.499 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6696): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6696): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6696): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6696): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6696): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6696):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6696):   adb logcat -s GAv4
,W/GAv4    ( 6696): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6696): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6696): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6696): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6696): Time to load native libraries: 2 ms (timestamps 6686-6688)
I/LibraryLoader( 6696): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6696): Binding Chromium to main looper Looper (main, tid 1) {cd6158e}
I/LibraryLoader( 6696): Expected native library version number "",actual native library version number ""
I/chromium( 6696): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6696): Initializing chromium process, singleProcess=true
W/art     ( 6696): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6696): ApplicationContext is null in ApplicationStatus
,W/chromium( 6696): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6696): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6696): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6696): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6696): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6696): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6696): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6696): Remote Branch: 
I/Adreno-EGL( 6696): Local Patches: 
I/Adreno-EGL( 6696): Reconstruct Branch: 
V/AudioPolicyService(  279): registerClient() client 0xb551cac0, uid 10079
,W/AudioManagerAndroid( 6696): Requires BLUETOOTH permission
I/NSApplication( 6696): Starting up...
,I/ActivityManager(  850): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6762 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  850): Killing 5091:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_10106/pid_5091/cgroup.procs: No such file or directory
,I/art     (  850): Explicit concurrent mark sweep GC freed 68032(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.592ms total 183.455ms
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  850): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6782 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  850): Killing 6510:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_10021/pid_6510/cgroup.procs: No such file or directory
,W/ResourcesManager( 6782): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  850): Killing 6544:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_6544/cgroup.procs: No such file or directory
,I/ActivityManager(  850): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6806 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/MusicStore( 6806): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6806): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
V/AlarmManager(  850): RTC_WAKEUP set : Alarm{198f6ca5 type 0 when 1452699341847 com.google.android.googlequicksearchbox} when 1452699341847
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6806): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6806): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ResourcesManager( 6806): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6806): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6806): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6806): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6806): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d8e7431: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6806): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6806): GMSCore installation verified
,I/ConfigStore( 6806): Config Database version: 1
,I/MediaRouter( 6806): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6806): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6806): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6806): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  850): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6839 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6806): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6806): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  850): Killing 6565:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6839): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6839): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  850): failed to open /acct/uid_10011/pid_6565/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:42.545 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/NotificationManager( 6806): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6839): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6839): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6839): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  850): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6871 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 22.092ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.507ms
,I/HubEmail( 6839): JNI_OnLoad()
I/HubEmail( 6839): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6839): registerNatives()
I/HubEmail( 6839): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6839): registerNativeMethods()
I/HubEmail( 6839): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6839): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 20.908ms
I/ActivityManager(  850): Killing 6591:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/Settings( 6839): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup(  850): failed to open /acct/uid_10038/pid_6591/cgroup.procs: No such file or directory
D/LGDMClient( 6871): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6871): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6871): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6871): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6871): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6871): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  850): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6900 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6871): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6871): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6871): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6871): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6871): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  850): Killing 6618:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_10051/pid_6618/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6900): onCreate
,W/AppUp4:DB( 6900):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6900):  setFingerPrint start
I/AppUp4:DB( 6900):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6900):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6900):  SDK version = 0
I/AppUp4:DB( 6900):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6900): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6900): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6900): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6900): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6900): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6900): onReceive
I/AppUp4:CustModeStarterReceiver( 6900): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6900): Context : android.app.ReceiverRestrictedContext@df47385
D/AppUp4:CustFacade( 6900): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6900): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6900): begin check event
I/AppUp4:CustModeStarterReceiver( 6900): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6900): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6900): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6900): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6900): handleAsyncCustNotification do not startCustService
I/ActivityManager(  850): Killing 6645:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  850): failed to open /acct/uid_10089/pid_6645/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3274): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3274): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3274): networkInfo.isConnected() = false
,I/ActivityManager(  850): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6922 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6922): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6922): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6922): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  850): Killing 6662:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 6922): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6922): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6922): [parse] Load xml
V/TelephonyAutoProfiling( 6922): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6922): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6922): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  850): failed to open /acct/uid_10061/pid_6662/cgroup.procs: No such file or directory
,V/DownloadManager( 3225): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3225): DownloadService onCreate
I/DownloadManager( 3225): in removeSpuriousFiles
V/DownloadManager( 3225): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/NotificationManager( 3225): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3225): created cursor android.database.sqlite.SQLiteCursor@c6684ea on behalf of 3225
I/DownloadManager( 3225): in trimDatabase
V/DownloadManager( 3225): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3225): created cursor android.database.sqlite.SQLiteCursor@5f15e78 on behalf of 3225
I/ActivityManager(  850): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6944 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3225): DownloadService onStartCommand
V/DownloadManager( 3225): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 4259): Checkin interval check for package: unspecified last checkin: 1452699312345 min interval config: 0 actual interval: 31788
V/DownloadManager( 3225): created cursor android.database.sqlite.SQLiteCursor@2ea005b6 on behalf of 3225
,I/CheckinService( 4259): Checking schedule, now: 1452699344161 next: 1452699342307
I/CheckinService( 4259): active receiver: enabled
,V/DownloadManager( 3225): DownloadService onDestroy
,I/CheckinService( 4259): Preparing to send checkin request
I/EventLogService( 4259): Accumulating logs since 1452699304815
,D/WeatherAncestor( 2667): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:35:44
D/UpdateThreadPoolManager( 2667): 2 : This is isUpdating : false
D/WeatherAncestor( 2667): connectivity changed - connection : true
D/Weather_cast( 2667): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2667): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:35:44
D/WeatherService( 2667): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/CheckinRequestBuilder( 4259): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  850): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6963 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  850): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2667): 2 : Utils getTopActivity com.lge.launcher2 / true
E/ActivityThread( 4259): Failed to find provider info for com.google.android.wearable.settings
,D/WeatherService( 2667): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2667): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6963): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  850): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6986 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     ( 6963): CheckpointMarkThreadRoots callback created = 0xb042d460
,W/ResourcesManager( 6986): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6986): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel_SMS( 6963): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6963): MmsConfig.loadMmsSettings
I/art     ( 6963): CheckpointMarkThreadRoots callback created = 0xb042d440
,I/Babel_SMS( 6963): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6963): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6963): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6963): MmsConfig.loadFromResources
E/Babel_SMS( 6963): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6963): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6963): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6963): found sensor: LGE Magnetometer Sensor, handle=10,
,D/SensorManager( 6963): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6963): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6963): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6963): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6963): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6963): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6963): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6963): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6963): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6963): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6963): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6963): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6963): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6963): found sensor: Motion Accel, handle=46
W/Settings( 6963): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6963): startup - clean
,I/MultiDex( 6986): VM with version 2.1.0 has multidex support
I/MultiDex( 6986): install
I/MultiDex( 6986): VM has multidex support, MultiDex support library is disabled.
I/Babel   ( 6963): deleted: false for 0
,V/JNIHelp ( 6986): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/jxcore-log( 6141): Test app app.js loaded
I/jxcore-log( 6141): 
,W/ActivityThread( 6986): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6986): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@165bb8de: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6986): Installed default security provider GmsCore_OpenSSL
I/art     (  850): Explicit concurrent mark sweep GC freed 14308(733KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.960ms total 150.852ms
,I/NotificationManager( 6986): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6986): com.google.android.gms: cancel(39789) by com.google.android.gms
I/chromium( 6141): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/AudioCapabilities( 6963): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6963): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6963): Unsupported mime audio/g726
,W/AudioCapabilities( 6963): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6963): Unsupported mime audio/wma-voice
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/MusicLeanback( 6806): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/LGDMClient( 6871): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6871): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/VideoCapabilities( 6963): Unsupported mime video/mjpg
W/Settings( 6839): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 6871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
,W/ContextImpl( 6871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
E/lowmemorykiller(  244): Error writing /proc/6900/oom_score_adj; errno=22
W/VideoCapabilities( 6963): Unsupported mime video/theora
,D/LGDMClient( 6871): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/LGDMClient( 6871): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 6871): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 6871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
D/LGDMClient( 6871): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/AudioCapabilities( 6963): Unsupported mime audio/evrc
I/ActivityManager(  850): Process com.lge.appbox.client (pid 6900) has died
W/AudioCapabilities( 6963): Unsupported mime audio/qcelp
W/VideoCapabilities( 6963): Unrecognized profile 2130706433 for video/avc
,E/LGDMClient( 6871): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6871): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6871): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6871): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,W/AudioCapabilities( 6963): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6963): Unsupported mime audio/qcelp
W/AudioCapabilities( 6963): Unsupported mime audio/evrc
D/LGDMClient( 6871): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     ( 6986): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6986): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/VideoCapabilities( 6963): Unsupported mime video/mp4v-esdp
I/ActivityManager(  850): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver: pid=7022 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/VideoCapabilities( 6963): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6963): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6963): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6963): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6963): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  850): Process com.google.android.setupwizard (pid 6922) has died
,V/AlarmManager(  850): RTC_WAKEUP set : Alarm{220f5af2 type 0 when 1452699342307 com.google.android.gms} when 1452699342307
I/vclib   ( 6963): onServiceConnected
,W/Babel   ( 6963): Attempted to change video mute state without an active call.
D/NativeLibraryUtils( 6986): Install completed successfully. count=14 extracted=0
,I/NotificationManager( 6963): com.google.android.talk: cancel(10436) by com.google.android.talk
I/AppUp4:AppBoxCP( 7022): onCreate
W/AppUp4:DB( 7022):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7022):  setFingerPrint start
,I/AppUp4:DB( 7022):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7022):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7022):  SDK version = 0
I/AppUp4:DB( 7022):  beforefinger == newfinger no write in DB
I/ActivityManager(  850): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7042 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  850): RTC_WAKEUP set : Alarm{376ba543 type 0 when 1452699345498 com.android.vending} when 1452699345498
D/AppUp4:AppBoxApplication( 7022): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7022): onReceive
I/AppUp4:CustModeStarterReceiver( 7022): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7022): Context : android.app.ReceiverRestrictedContext@2651eace
D/AppUp4:CustFacade( 7022): isCustomizationCompleted : false
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:45.604 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/AppUp4:CustFacade( 7022): isSimDevice : true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd( 6963): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6963): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6963): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6963): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6963): propertyValue:false
I/ActivityManager(  850): Process com.google.process.gapps (pid 3989) has died
,D/AppUp4:CustModeStarterReceiver( 7022): begin check event
I/AppUp4:CustModeStarterReceiver( 7022): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7022): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7022): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7022): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7022): handleAsyncCustNotification do not startCustService
I/Babel   ( 6963): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  850): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7065 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/LgeMiscReceiver( 3274): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3274): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3274): networkInfo.isConnected() = true
D/PhoneState( 3274): setPdpRejectCasuse : false
I/ActivityManager(  850): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7082 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/GservicesProvider( 7065): Gservices pushing to system: true; secure/global: true
,D/PhoneMonitor( 7082): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7082): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7082): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 3225): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3225): DownloadService onCreate
D/WeatherAncestor( 2667): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:35:45
I/DownloadManager( 3225): in removeSpuriousFiles
V/DownloadManager( 3225): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3225): created cursor android.database.sqlite.SQLiteCursor@19ea24 on behalf of 3225
D/UpdateThreadPoolManager( 2667): 2 : This is isUpdating : false
D/WeatherAncestor( 2667): connectivity changed - connection : true
D/Weather_cast( 2667): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2667): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:35:45
I/NotificationManager( 3225): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3225): in trimDatabase
V/DownloadManager( 3225): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3225): created cursor android.database.sqlite.SQLiteCursor@2c37d98d on behalf of 3225
D/WeatherService( 2667): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  850): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2667): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2667): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2667): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,V/DownloadManager( 3225): DownloadService onStartCommand
V/DownloadManager( 3225): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/PhoneMonitor( 7082): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 7082): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7082): [parse] Load xml
I/GoogleHttpClient( 7065): GMS http client unavailable, use old client
V/TelephonyAutoProfiling( 7082): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7082): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3225): created cursor android.database.sqlite.SQLiteCursor@281d8490 on behalf of 3225
,D/PhoneMonitor( 7082): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3225): DownloadService onDestroy
,I/GoogleHttpClient( 7065): GMS http client unavailable, use old client
I/CheckinService( 4259): Checkin interval check for package: unspecified last checkin: 1452699312345 min interval config: 0 actual interval: 33734
D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): CdmEngine::OpenSession
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  850): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7123 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=403897333
D/Finsky  ( 7042): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ResourcesManager( 7123): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  850): Message: 20
D/BluetoothManagerService(  850): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e9e025:true
,D/BluetoothAdapterService(832602344)( 1968): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1074a37e
D/BluetoothAdapterService(832602344)( 1968): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1074a37e
,D/Finsky  ( 7042): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7042): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7042): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7042): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  850): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7158 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 311us total 22.951ms
,V/LGMDMManager( 7123): Create singleton instance
I/art     (  310): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.032ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.882ms
,I/ActivityManager(  850): Process com.google.android.music:main (pid 6806) has died
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
V/DownloadManager( 3225): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3225): created cursor android.database.sqlite.SQLiteCursor@cd6158e on behalf of 7042
D/Ads     ( 7042): Skipping gmscore version check
,D/Finsky  ( 7042): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7042): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7042): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/dex2oat ( 7167): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/AudioManager( 7123): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7158): Quickset Services start...
D/Finsky  ( 7042): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/UEI.SmartControl( 7158): Manufacture = LGE
,D/UEI.SmartControl( 7158): File observer start...
,E/UEI.SmartControl( 7158): IR Port is disabled: false
D/UEI.SmartControl( 7158): Starting file observer...
D/UEI.SmartControl( 7158): Extracting JNI libs...
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,D/UEI.SmartControl( 7158): --- this system supports 32-bit or 64-bit only
D/LocationInitializer( 4259): Restart initialization of location
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1732): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,I/CheckinService( 4259): Checkin interval check for package: unspecified last checkin: 1452699312345 min interval config: 0 actual interval: 34547
I/dex2oat ( 7167): dex2oat took 149.334ms (threads: 4)
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,I/art     ( 6986): CheckpointMarkThreadRoots callback created = 0xb053e3b0
I/Adreno-EGL( 6986): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6986): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6986): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6986): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6986): Remote Branch: 
I/Adreno-EGL( 6986): Local Patches: 
I/Adreno-EGL( 6986): Reconstruct Branch: 
,I/art     ( 6986): CheckpointMarkThreadRoots callback created = 0xb053e3a0
,I/art     ( 6986): Background partial concurrent mark sweep GC freed 16100(1131KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 10MB/17MB, paused 6.558ms total 58.305ms
,I/AudioManager( 7123): getMode name:com.lge.qremote
,W/ContextImpl( 3656): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/Adreno-EGL( 6986): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6986): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6986): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6986): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6986): Remote Branch: 
I/Adreno-EGL( 6986): Local Patches: 
I/Adreno-EGL( 6986): Reconstruct Branch: 
,D/UEI.SmartControl( 7158): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7158): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7158): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7158): --- Selecting new region: 2
I/UEI.SmartControl( 7158): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7158): Platform has CIR...
D/UEI.SmartControl( 7158): NO CIR support, need to check package...
I/UEI.SmartControl( 7158): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 7158): QS Service created
E/UEI.SmartControl( 7158): QS start get config
D/Finsky  ( 7042): [880] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7042): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  850): Killing 6839:com.lge.email/u0a21 (adj 15): empty #11
D/UEI.SmartControl( 7158): Loading JNI Libs...
,D/UEI.SmartControl( 7158):  configuring local db...
I/Adreno-EGL( 6986): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6986): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6986): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6986): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6986): Remote Branch: 
I/Adreno-EGL( 6986): Local Patches: 
I/Adreno-EGL( 6986): Reconstruct Branch: 
,W/libprocessgroup(  850): failed to open /acct/uid_10021/pid_6839/cgroup.procs: No such file or directory
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/UEI.SmartControl( 7158):  ---- Has DB8: true
,D/UEI.SmartControl( 7158): QS start statue = true Error code = 0
D/UEI.SmartControl( 7158): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7158): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7158): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7158): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7158): IrrcClient ++ 
D/irrcClient( 7158): getIrrcService ++ 
,D/irrcClient( 7158): getIrrcService -- 
D/irrcClient( 7158): IrrcClient -- 
W/irrc_jni( 7158): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7158): Services init done
I/UEI.SmartControl( 7158): Device manager: loading config....
D/UEI.SmartControl( 7158): QS Service init finished
D/UEI.SmartControl( 7158): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7158): QS Service version code: 1073
D/UEI.SmartControl( 7158): Service requested: Control
D/UEI.SmartControl( 7158): Config is loaded...
D/UEI.SmartControl( 7158):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7158): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7158): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7158): Internal service binding...
D/UEI.SmartControl( 7158): -----IControl: 11
D/UEI.SmartControl( 7158): Caller: com.lge.qremote
D/UEI.SmartControl( 7158): ------------ IControl registerCallback...
I/UEI.SmartControl( 7158): Registering callback...
,D/UEI.SmartControl( 7158): -----IControl: 19
,D/UEI.SmartControl( 7158): Caller: com.lge.qremote
I/UEI.SmartControl( 7158): Registering Services Ready callback...
I/UEI.SmartControl( 7158): Notify client services are ready...
D/UEI.SmartControl( 7158): -----IControl: 8
D/UEI.SmartControl( 7158): Caller: com.lge.qremote
I/AudioManager( 7123): getMode name:com.lge.qremote
,I/ActivityManager(  850): Killing 7022:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/ActivityManager(  850): Killing 6871:com.lge.lgdmsclient/1000 (adj 15): empty #12
,W/libprocessgroup(  850): failed to open /acct/uid_10011/pid_7022/cgroup.procs: No such file or directory
,W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_6871/cgroup.procs: No such file or directory
I/AudioManager( 7123): getMode name:com.lge.qremote
I/AudioManager( 7123): getMode name:com.lge.qremote
,D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 114597509701; DSPS: 3853191; Offset : -2997333011
I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=1900045219
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): L3 Terminate.
I/MusicWidget( 2587): mDelayedStopHandler : unbind
,I/MusicBrowser( 2718): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2718): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2718): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/MusicBrowser( 2718): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2718): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2718): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2718): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2718): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  850):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@433798acom.lge.music.MediaPlaybackService$6@3aefbfb
,D/MusicBrowser( 2718): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2718): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2718): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2718): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2718): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@240dc301
I/MusicBrowser( 2718): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2718): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2718): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2718): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2718): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2718): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2718): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2718): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2718): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2718): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2718): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2718): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2718): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2718): reset
V/MediaPlayer[Native]( 2718): setListener
V/MediaPlayer[Native]( 2718): disconnect
V/MediaPlayer[Native]( 2718): destructor
V/AudioFlinger(  279): releasing 18 from 2718 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/MediaPlayer[Native]( 2718): disconnect
,D/MusicBrowser( 2718): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2718): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2718): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2718): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2718): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2718): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2718): [SmartShareManagerClient] unregisterListener: 23720984
,W/SmartShareClient( 2718): [SmartShareManagerClient] unregisterListener invalid listener: 23720984
I/SmartShareClient( 2718): [SmartShareManagerClient] terminate service: 2718/MediaPlaybackService/801107439
E/HomeCloudIF( 2718): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2718): [SmartShareManagerClient] unbindService context:android.app.Application@50c6e71
V/CloudHub( 2718): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2718): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2718): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2718): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2718): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  850): Killing 6944:com.lge.drmservice/u0a51 (adj 15): empty #11
I/CloudHub( 2718): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29991
W/libprocessgroup(  850): failed to open /acct/uid_10051/pid_6944/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 4259): Classify the device as Phone.
D/libc-netbsd( 4259): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4259): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4259): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4259): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 4259): propertyValue:false
,D/libc-netbsd( 4259): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4259): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4259): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4259): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4259): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4259): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 4259): Sending checkin request (9726 bytes)
,I/CheckinRequestBuilder( 4259): Checkin reason type: 8 attempt count: 1
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
E/ActivityThread( 4259): Failed to find provider info for com.google.android.wearable.settings
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4259): Classify the device as Phone.
,I/CheckinTask( 4259): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4259): Checking schedule, now: 1452699351864 next: 1453226600859
I/CheckinService( 4259): active receiver: disabled
,I/CheckinService( 4259): Checking schedule, now: 1452699351942 next: 1453226600859
I/CheckinService( 4259): active receiver: disabled
,D/CheckinService( 4259): Recording last checkin time for package unspecified as 1452699351951
,I/ActivityManager(  850): Killing 6696:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  850): failed to open /acct/uid_10079/pid_6696/cgroup.procs: No such file or directory
,V/SetupWizard( 7082): Connected to Gservices successfully
,I/ActivityManager(  850): Killing 6762:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  850): failed to open /acct/uid_10048/pid_6762/cgroup.procs: No such file or directory
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7158): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  850): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  850): Handling package changes for user 0
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  850): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7266 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/NotificationManager( 6963): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6963): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6963): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AppUp4:AppBoxCP( 7266): onCreate
,W/AppUp4:DB( 7266):  [AppBoxDatabaseHelper] construct
V/JNIHelp ( 6963): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:DB( 7266):  setFingerPrint start
I/AppUp4:DB( 7266):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7266):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7266):  SDK version = 0
I/AppUp4:DB( 7266):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7266): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7266): onReceive
,I/AppUp4:CustModeStarterReceiver( 7266): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7266): Context : android.app.ReceiverRestrictedContext@2651eace
D/AppUp4:CustFacade( 7266): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7266): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7266): begin check event
,I/AppUp4:CustModeStarterReceiver( 7266): Event For Nothing, skip.
W/System  ( 6963): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6963): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  850): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7289 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationService(  850): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  850): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  850): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  850): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,W/ResourcesManager(  850): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  850): Process com.android.vending (pid 7042) has died
,I/art     (  850): Explicit concurrent mark sweep GC freed 31519(1488KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.427ms total 178.437ms
,V/BackupManagerService(  850): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  850): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2231ee17
,W/ResourcesManager( 7289): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType(  850): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/ResourcesManager( 7289): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7289): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  850): applying state to connected service
,I/AppConfig( 7289): Total System Memory = 906309632
,I/GalleryUtils( 7289): Application Heap = 96 MB
I/AppConfig( 7289): App Tier : NOT_DEF
D/SystemHelper( 7289): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  850): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7310 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7310): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7310): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7310): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7310): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7310): BUILD Country: EU
I/SystemConfig( 7310): BUILD Operator: OPEN
,I/ActivityManager(  850): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7335 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  850): Killing 6782:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_10086/pid_6782/cgroup.procs: No such file or directory
,I/SystemConfig( 7310): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7310): existFile = false
I/SystemConfig( 7310): canReadFile = false
I/SystemConfig( 7310): systemFeature RCS result false
D/SystemConfig( 7310): refreshRcsSupport() :false
,I/LockScreenSettings( 7335): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7335): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7335): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7335): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7335): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7335): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  850): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7352 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  850): Killing 2718:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  279): 2718 died, releasing its sessions
,V/AudioFlinger(  279):  pid 1749 @ 0
V/AudioFlinger(  279):  pid 3274 @ 1
V/AudioFlinger(  279):  pid 3274 @ 2
,W/libprocessgroup(  850): failed to open /acct/uid_10028/pid_2718/cgroup.procs: No such file or directory
W/ResourcesManager( 7352): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  850): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7382 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 94 ms] updated apps [took 94 ms] 
,I/ActivityManager(  850): Killing 7082:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  850): failed to open /acct/uid_10038/pid_7082/cgroup.procs: No such file or directory
,D/Finsky  ( 7382): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7382): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7382): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7382): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7382): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3225): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3225): created cursor android.database.sqlite.SQLiteCursor@2b8ca1af on behalf of 7382
D/Ads     ( 7382): Skipping gmscore version check
D/Finsky  ( 7382): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7382): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7382): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 7382): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PackageBroadcastService( 4259): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4259): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4259): updateResources: need to parse f{com.google.android.gms}
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:35:57.624 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 4259): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4259): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  850): Killing 6986:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  850): failed to open /acct/uid_10006/pid_6986/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  850): Killing 7158:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7123): android.os.DeadObjectException
,W/libprocessgroup(  850): failed to open /acct/uid_10089/pid_7158/cgroup.procs: No such file or directory
W/ActivityManager(  850): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/System.err( 7123): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7123): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7123): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7123): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7123): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7123): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7123): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7123): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7123): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7123): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7123): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7123): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7123): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7123): android.os.DeadObjectException
W/System.err( 7123): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7123): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7123): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7123): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7123): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7123): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7123): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7123): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7123): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7123): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7123): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7123): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7123): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  850): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7443 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7443): Quickset Services start...
,I/UEI.SmartControl( 7443): Manufacture = LGE
D/UEI.SmartControl( 7443): File observer start...
E/UEI.SmartControl( 7443): IR Port is disabled: false
D/UEI.SmartControl( 7443): Starting file observer...
D/UEI.SmartControl( 7443): Extracting JNI libs...
D/UEI.SmartControl( 7443): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7443): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7443): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7443): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/PowerManagerServiceEx(  850): acquireWakeLockInternal: lock=305997825, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=850
,I/UEI.SmartControl( 7443): --- Selecting new region: 2
I/UEI.SmartControl( 7443): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7443): Platform has CIR...
D/UEI.SmartControl( 7443): NO CIR support, need to check package...
I/UEI.SmartControl( 7443): Model: LG-D722 uses JNI
D/WeatherService( 2667): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:36:0
D/WeatherService( 2667): 2 : TimeTick Intent And Screen On
D/WeatherService( 2667): 2 : SDK version : 21
W/ActivityManager(  850): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/UEI.SmartControl( 7443): QS Service created
D/Weather.Utils( 2667): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2667): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2667): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2667): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2667): 2 : This is isUpdating : false
D/WeatherService( 2667): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2667): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2667): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2667): 2 : Fixed theme : optimus
D/WeatherReflect( 2667): 2 : Map key string is -2
,D/lim     ( 2667): 2 : time = 16:36
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/WeatherReflect( 2667): Model Name : LG-D722
D/WeatherTheme( 2667): 2 : Different view - status_min_formatted : 35 != 36
D/WeatherTheme( 2667): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2667): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
E/UEI.SmartControl( 7443): QS start get config
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2667): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/Weather4x2_optimus( 2667): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
,D/Weather4x2_optimus( 2667): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2667): forecast size is 0
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2667): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2667): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2667): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2667): url is : null
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2667): 2 : update view, appWidgetId: 2
D/WeatherService( 2667): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:36:0
D/PowerManagerServiceEx(  850): releaseWakeLockInternal: lock=305997825 [*alarm*], flags=0x0
,D/UEI.SmartControl( 7443): Loading JNI Libs...
D/UEI.SmartControl( 7443):  configuring local db...
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/UEI.SmartControl( 7443):  ---- Has DB8: true
,D/UEI.SmartControl( 7443): QS start statue = true Error code = 0
D/UEI.SmartControl( 7443): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7443): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7443): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7443): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7443): IrrcClient ++ 
D/irrcClient( 7443): getIrrcService ++ 
,D/irrcClient( 7443): getIrrcService -- 
D/irrcClient( 7443): IrrcClient -- 
W/irrc_jni( 7443): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7443): Services init done
I/UEI.SmartControl( 7443): Device manager: loading config....
D/UEI.SmartControl( 7443): QS Service init finished
,D/UEI.SmartControl( 7443): QS Service version name: 0.1.73
D/UEI.SmartControl( 7443): QS Service version code: 1073
D/UEI.SmartControl( 7443): Config is loaded...
D/UEI.SmartControl( 7443): Service requested: Control
I/ActivityManager(  850): Killing 7123:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7443):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7443): Notify AllClients services are ready: 0
,W/libprocessgroup(  850): failed to open /acct/uid_10106/pid_7123/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7443): Internal service binding...
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
D/WifiController(  850): battery changed pluggedType: 2
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:36:03.656 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7443): Internal timer expired: 1
,D/UEI.SmartControl( 7443): Service.onUnbind: IControl
D/UEI.SmartControl( 7443): Service.onDestroy
D/UEI.SmartControl( 7443): Shutdown IRRCPlayer... 
,W/irrc_jni( 7443): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7443): ~IrrcClient ++ 
D/irrcClient( 7443): ~IrrcClient -- 
W/irrc_jni( 7443): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7443): Blaster closed
D/UEI.SmartControl( 7443): Blaster closed
D/UEI.SmartControl( 7443): Shut down QS...
,D/UEI.SmartControl( 7443): Stopped file observer...
I/UEI.SmartControl( 7443): QS lib stop result = true
D/UEI.SmartControl( 7443): QS shutdown complete
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:36:06.678 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 134598253079; DSPS: 4508575; Offset : -2997321064
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:36:09.697 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:36:12.718 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  850): ELAPSED_WAKEUP set : Alarm{153433d type 2 when 144506 com.google.android.gms} when 144506
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1732): Vacuum at: now=1452699378136 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  850): ALS enabled for SRE
D/PowerManagerServiceEx(  850): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28785 ms ago)
,D/qdlights(  850): set_light_backlight: 253
,D/qdlights(  850): set_light_backlight: 250
,D/qdlights(  850): set_light_backlight: 246
,D/qdlights(  850): set_light_backlight: 243
,D/qdlights(  850): set_light_backlight: 240
,D/qdlights(  850): set_light_backlight: 236
,D/qdlights(  850): set_light_backlight: 233
,D/qdlights(  850): set_light_backlight: 230
,D/qdlights(  850): set_light_backlight: 226
,D/qdlights(  850): set_light_backlight: 223
,D/qdlights(  850): set_light_backlight: 220
,D/qdlights(  850): set_light_backlight: 216
,D/qdlights(  850): set_light_backlight: 213
,D/qdlights(  850): set_light_backlight: 210
,D/qdlights(  850): set_light_backlight: 206
,D/qdlights(  850): set_light_backlight: 203
,D/qdlights(  850): set_light_backlight: 200
,D/qdlights(  850): set_light_backlight: 196
,D/qdlights(  850): set_light_backlight: 193
,D/qdlights(  850): set_light_backlight: 190
,D/qdlights(  850): set_light_backlight: 186
,D/qdlights(  850): set_light_backlight: 183
,D/qdlights(  850): set_light_backlight: 180
,D/qdlights(  850): set_light_backlight: 176
,D/qdlights(  850): set_light_backlight: 173
,D/qdlights(  850): set_light_backlight: 170
,D/qdlights(  850): set_light_backlight: 166
,D/qdlights(  850): set_light_backlight: 163
,D/qdlights(  850): set_light_backlight: 160
,D/qdlights(  850): set_light_backlight: 156
,D/qdlights(  850): set_light_backlight: 153
,D/qdlights(  850): set_light_backlight: 150
,D/qdlights(  850): set_light_backlight: 146
,D/qdlights(  850): set_light_backlight: 143
,D/qdlights(  850): set_light_backlight: 140
,D/qdlights(  850): set_light_backlight: 136
,D/qdlights(  850): set_light_backlight: 133
,D/qdlights(  850): set_light_backlight: 130
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  850): set_light_backlight: 126
,D/qdlights(  850): set_light_backlight: 123
,D/qdlights(  850): set_light_backlight: 120
,D/qdlights(  850): set_light_backlight: 116
,D/qdlights(  850): set_light_backlight: 113
,D/qdlights(  850): set_light_backlight: 110
,D/qdlights(  850): set_light_backlight: 106
,D/qdlights(  850): set_light_backlight: 103
,D/qdlights(  850): set_light_backlight: 100
,D/qdlights(  850): set_light_backlight: 96
,D/qdlights(  850): set_light_backlight: 93
,D/qdlights(  850): set_light_backlight: 90
,D/qdlights(  850): set_light_backlight: 86
,D/qdlights(  850): set_light_backlight: 83
,D/qdlights(  850): set_light_backlight: 80
,D/qdlights(  850): set_light_backlight: 76
,D/qdlights(  850): set_light_backlight: 73
,D/qdlights(  850): set_light_backlight: 70
,D/qdlights(  850): set_light_backlight: 66
,D/qdlights(  850): set_light_backlight: 63
,D/qdlights(  850): set_light_backlight: 60
,D/qdlights(  850): set_light_backlight: 56
,D/qdlights(  850): set_light_backlight: 53
,D/qdlights(  850): set_light_backlight: 50
,D/qdlights(  850): set_light_backlight: 46
,D/qdlights(  850): set_light_backlight: 43
,D/qdlights(  850): set_light_backlight: 40
,D/qdlights(  850): set_light_backlight: 36
,D/qdlights(  850): set_light_backlight: 33
,D/qdlights(  850): set_light_backlight: 30
,D/qdlights(  850): set_light_backlight: 26
,D/qdlights(  850): set_light_backlight: 23
,D/qdlights(  850): set_light_backlight: 20
,D/qdlights(  850): set_light_backlight: 16
,D/qdlights(  850): set_light_backlight: 13
,D/qdlights(  850): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:36:24.77 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:36:27.789 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 154599523383; DSPS: 5163977; Offset : -2997331874
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  850): ALS enabled for SRE
D/PowerManagerServiceEx(  850): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35781 ms ago)
I/PowerManagerService(  850): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  850): ALS enabled for SRE
D/PowerManagerServiceEx(  850): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35792 ms ago)
W/ContextImpl(  850): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  850): Sleeping (uid 1000)...
D/LPWGController(  850): [updateScreenState] screen on = false
D/LPWGController(  850): disable proximity sensor
D/LPWGController(  850): enable proximity sensor
,I/SensorManager(  850): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1e17aa8a] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  850): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  850): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  850): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  850): activate: handle is 48, enable
V/sensors_hal_Ctx(  850): activate sensors is 1400000000000
D/sensors_hal_Thresh(  850): enable: handle=48
I/sensors_hal_SAM(  850): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  850): waitForResponse: timeout=1000
V/sensors_hal_SAM(  850): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  850): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  850): enable: Received response: 0
D/PowerManagerServiceEx(  850): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35831 ms ago)
I/Adreno-EGL(  850): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  850): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  850): Build Date: 03/02/15 Mon
I/Adreno-EGL(  850): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  850): Remote Branch: 
I/Adreno-EGL(  850): Local Patches: 
I/Adreno-EGL(  850): Reconstruct Branch: 
,D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1023 us)
,I/Sensors (  436): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  850): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  850): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  850): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  850): processInd: handle 48, count=1
V/sensors_hal_Thresh(  850): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  850): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  850): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  850): poll: count: 256
I/sensors_hal_Ctx(  850): poll: released wakelock sensor_ind
D/sensors_hal_Util(  850): waitForResponse: timeout=0
D/LPWGController(  850): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  850): current mode = 1  value = 1 1
I/LPWGController(  850): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
,I/LPWGController(  850): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  850): set_light_backlight: 0
,I/SensorManager(  850): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  850): activate: handle is 46, disable
V/sensors_hal_Ctx(  850): activate sensors is 1000000000000
D/sensors_hal_LP2(  850): enable: handle=46
D/sensors_hal_LP2(  850): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  850): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  247): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  247): hwc_blank: Blanking display: 0
I/DisplayManagerService(  850): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/sensors_hal_SAM(  850): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  850): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,V/ActivityManager(  850): Display changed displayId=0
,D/DSDPConnection( 1749): Display #0 changed.
,D/qdhwcomposer(  247): hwc_blank: Done blanking display: 0
D/SurfaceControl(  850): Excessive delay in setPowerMode(): 188ms
,I/qdhwcomposer(  247): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  850): Got set_interactive hint
D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1335): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1374): notifyScreenOffLocked
,D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1374): handleNotifyScreenOff
D/SmartCoverViewMediator( 1335): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1335): handleNotifyScreenOFF
D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
,D/WifiServerServiceExt(  850): sendKtScanInterval  mRtspPlay : false
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 16:36:30.095 DNS addrs= 192.168.1.1, 0.0.0.0, 
V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 850
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
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
I/WifiServerServiceExt(  850): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
,D/GpsLocationProvider(  850): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1803): lockStatus = 0
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/NfcServiceNXP( 1786): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1786): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
,D/NfcService( 1786): screenState= 3
D/NfcService( 1786): Discovery configuration equal, not updating.
D/LEDHandler( 1803): RESTART MSG
D/Ulp_jni (  850): JNI:system_update. Event-0
D/SplitWindow(  850): check instance of lgWin Window{145f1371 u0 SearchPanel}
,D/InputDispatcher(  850): Window went away: Window{3058a36c u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2667): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:36:30
,D/WeatherService( 2667): 2 : ACTION screen on
D/WeatherService( 2667): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2667): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2667): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:36:30
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  850): ACTION_SCREEN_ON
D/AppCleanupService( 4102): android.intent.action.SCREEN_ON
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 850
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
D/WifiController(  850): CMD_SCREEN_OFF 
D/WifiController(  850): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  850): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): updateLightsLocked : turn on led
D/VolumeVibrator( 1803): clear
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
,I/Sensors (  436): sns_pwr.c(301):releasing wakelock
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
D/WeatherService( 2667): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:36:30
D/WeatherService( 2667): 2 : ACTION screen off
,D/WeatherService( 2667): 2 : TimeTick Receiver Unregister
D/WeatherService( 2667): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:36:30
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  850): ACTION_SCREEN_OFF
D/AppCleanupService( 4102): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4102): AppUsageStatsSaveTask
,E/NxpNfcJni( 1786): getReconnectState = 0x0
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1786): getDefaultRoute
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: 0
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 1
E/NxpNfcJni( 1786): getReconnectState = 0x0
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  850): ELAPSED_WAKEUP set : Alarm{1ecde556 type 2 when 161665 com.android.systemui} when 161665
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
,V/TelecomServiceImpl( 1749): getCallState : 0
D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
,D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 174600590928; DSPS: 5819372; Offset : -2997332756
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  850): battery changed pluggedType: 2
D/PowerManagerServiceEx(  850): acquireWakeLockInternal: lock=305997825, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=850
,V/AlarmManager(  850): ELAPSED_WAKEUP set : Alarm{100f09d7 type 2 when 187583 com.google.android.gms} when 187583
D/PowerManagerServiceEx(  850): releaseWakeLockInternal: lock=305997825 [*alarm*], flags=0x0
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 44880(2MB) AllocSpace objects, 28(448KB) LOS objects, 39% free, 13MB/22MB, paused 2.070ms total 171.332ms
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 4948 seconds from now (1452699421478)
,D/GetConfigurationSnapshotOperation( 1732): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  850): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
V/AlarmManager(  850): ELAPSED_WAKEUP set : Alarm{16a7c65c type 2 when 188330 android} when 188330
,I/System.out( 1732): propertyValue:false
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  850): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  850): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  850): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  850): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  850): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  850): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 194601252796; DSPS: 6474754; Offset : -2997342275
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 214602026851; DSPS: 7130139; Offset : -2997331575
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  850): RTC_WAKEUP set : Alarm{3ff484f4 type 0 when 1452699458303 com.google.android.gms} when 1452699458303
,I/EventLogService( 4259): Aggregate from 1452699344220 (log), 1452697658181 (data)
,I/art     (  850): Explicit concurrent mark sweep GC freed 55396(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 3.367ms total 248.103ms
,D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 234602781947; DSPS: 7785524; Offset : -2997338977
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  850): battery changed pluggedType: 2
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 254603455846; DSPS: 8440906; Offset : -2997338444
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 274604214536; DSPS: 9096291; Offset : -2997340845
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 294604985726; DSPS: 9751676; Offset : -2997332463
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  850): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 314605634781; DSPS: 10407057; Offset : -2997324433
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  850): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  850): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1968): Disconnected process message: 10, size: 0
W/Settings(  850): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  850): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  850): battery changed pluggedType: 2
I/jxcore-log( 6141): --= Surplus to requirements =--
I/jxcore-log( 6141): 
I/jxcore-log( 6141): ****TEST TOOK:  ms ****
I/jxcore-log( 6141): 
I/jxcore-log( 6141): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6141): 
,D/AndroidRuntime( 7623): 
D/AndroidRuntime( 7623): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7623): CheckJNI is OFF
,D/AndroidRuntime( 7623): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  850): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  850): Killing 6141:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,I/WindowState(  850): WIN DEATH: Window{2030bc1f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  850): Skipping PackageSetting{10271d29 com.example.hello/10317} due to missing metadata
,D/InputDispatcher(  850): Focus left window: Window{2030bc1f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  850): Window went away: Window{2030bc1f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  850):   Force finishing activity ActivityRecord{17b3bce0 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  850): Display changed displayId=0
D/DSDPConnection( 1749): Display #0 changed.
W/ActivityManager(  850): Spurious death for ProcessRecord{29c6e519 6141:com.test.thalitest/u0a316}, curProc for 6141: null
I/ActivityManager(  850): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  850):   Force finishing activity ActivityRecord{17b3bce0 u0 com.test.thalitest/.MainActivity t222 f}
,W/ActivityManager(  850): Duplicate finish request for ActivityRecord{17b3bce0 u0 com.test.thalitest/.MainActivity t222 f}
,I/art     ( 4259): Explicit concurrent mark sweep GC freed 12308(731KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 14MB/18MB, paused 782us total 76.484ms
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1877): [Launcher.java:5203:onStart()]onStart
,W/System.err( 3656): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
,I/[LGHome]EVENT( 1877): [Launcher.java:776:onResume()]onResume
I/InputReader(  850): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  850): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7655 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/System.err( 3656): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3656): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3656): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3656): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3656): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3656): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3656): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3656): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3656): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3656): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3656): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1877): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/art     ( 1939): Explicit concurrent mark sweep GC freed 10300(677KB) AllocSpace objects, 3(71KB) LOS objects, 39% free, 12MB/21MB, paused 1.853ms total 155.751ms
,I/[LGHome]LGActivityUtil( 1877): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1877): [Launcher.java:929:onResume()]onResume end
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
I/Activity( 1877): Activity.onPostResume() called 
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
,W/[LGHome]LGWallpaperInfo( 1877): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1877): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,I/SystemUI[Framework](  850): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/PhoneWindowManagerEx(  850): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  850): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  850): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@83bedf7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  850): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  850): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  850): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  850): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@83bedf7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/InputDispatcher(  850): Focus entered window: Window{31037a9d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
,W/ResourcesManager( 1374): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1374): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/art     (  850): Explicit concurrent mark sweep GC freed 12385(953KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.924ms total 253.723ms
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/art     (  850): WaitForGcToComplete blocked for 126.979ms for cause Explicit
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
,I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1877): [setNavigationBarColor] color=0x 0
W/ResourcesManager( 7655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7655): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7655): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 1374): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourcesManager( 1374): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1374): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1374): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): handleShortcutListChanged...
,D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
,W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
,D/KeyguardModel( 1374): handleShortcutListChanged...
,D/administrator(  850): Handling package changes for user 0
,I/art     (  850): Explicit concurrent mark sweep GC freed 4275(246KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 6.329ms total 266.058ms
,W/InputMethodManagerService(  850): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  850): Got RemoteException sending setActive(false) notification to pid 6141 uid 10316
I/LGEmail ( 7655): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7655): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  850): Timeline: Activity_windows_visible id: ActivityRecord{2d0be3c6 u0 com.lge.launcher2/.Launcher t221} time:327960
,W/IInputConnectionWrapper( 1877): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
E/b       ( 1586): Unable to connect to the editor to retrieve text... will retry later
D/AndroidRuntime( 7623): Shutting down VM
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1877): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/NotificationService(  850): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  850): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  850): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/TaskPersister(  850): removeObsoleteFile: deleting file=222_task.xml
,I/PackageChangeReceiver( 7655): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,W/ResourcesManager(  850): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AppUp4:PreloadHelper( 7266): added Exclude : com.test.thalitest
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourceType(  850): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  850): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7682 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  850): Killing 6963:com.google.android.talk/u0a61 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  850): failed to open /acct/uid_10061/pid_6963/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7682): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7682): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7682): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7682): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7682): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
E/SQLiteDatabase( 7682): Failed to open database '/data/data/com.android.settings/databases/vibrateuserpattern.db'.
E/SQLiteDatabase( 7682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 7682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 7682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 7682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 7682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 7682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 7682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 7682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 7682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7682): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7682): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/SQLiteDatabase( 7682): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 7682): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 7682): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 7682): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 7682): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 7682): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 7682): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7682): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7682): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7682): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 7682): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7682): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7682): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 7682): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/AndroidRuntime( 7682): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 7682): FATAL EXCEPTION: main
E/AndroidRuntime( 7682): Process: com.android.settings, PID: 7682
E/AndroidRuntime( 7682): java.lang.RuntimeException: Unable to get provider com.android.settings.vibratecreation.VibrateUserPatternProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7682): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 7682): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 7682): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 7682): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 7682): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7682): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7682): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7682): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 7682): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7682): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7682): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 7682): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 7682): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 7682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 7682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 7682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 7682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 7682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 7682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 7682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 7682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7682): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7682): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/AndroidRuntime( 7682): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 7682): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 7682): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 7682): 	... 11 more

```
